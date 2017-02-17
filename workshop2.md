#Workshop 2
###Login Website

**This workshop like a workshop 1 but this workshop difference**

**Workshop 2** run at your local by python server.
This workshop use Library and keywords. eg. **Suite Setup, Suite Teardown, Test Setup, Test Template**.
This workshop use Variables.
This workshop use **gherkin** style for test case.

**Task**
1.Start Server with Python.
2.Run robot with valid_login.robot
3.Run robot with invalid_login.robot
4.Run robot with gherkin_login.robot
5.Run robot all file

**Valid Login**
valid_login.robot

| No | Test Procedure                                                                                        | Expected Result             | Test Result | Remark |
|----|-------------------------------------------------------------------------------------------------------|-----------------------------|-------------|--------|
| 1  | Open website demo login                                                                               | To show login page          |             |        |
| 2  | Type demo to input text username_field.  Type mode to input password password_field.  Submit to login | Welcome Page Should Be Open |             |        |


**invalid Login**
invalid_login.robot

| No | Test Procedure                                                                                          | Expected Result                                      | Test Result | Remark |
|----|---------------------------------------------------------------------------------------------------------|------------------------------------------------------|-------------|--------|
| 1  | Open website demo login                                                                                 | To show login page                                   |             |        |
| 2  | Type invalid to input text username_field. Type mode to input password password_field. Submit to login  | Location Should Be error. Title Should Be,Error Page |             |        |
| 3  | Type demo to input text username_field. Type whatever to input password password_field. Submit to login | Location Should Be error. Title Should Be,Error Page |             |        |
| 4  | Type "" to input text username_field. Type mode to input password password_field. Submit to login       | Location Should Be error. Title Should Be,Error Page |             |        |
| 5  | Type demo to input text username_field. Type "" to input password password_field. Submit to login       | Location Should Be error. Title Should Be,Error Page |             |        |
| 6  | Type "" to input text username_field. Type "" to input password password_field. Submit to login         | Location Should Be error. Title Should Be,Error Page |             |        |

**Valid Login with gherkin style**
gherkin_login.robot

| No | Test Procedure                                                                                        | Expected Result             | Test Result | Remark |
|----|-------------------------------------------------------------------------------------------------------|-----------------------------|-------------|--------|
| 1  | Open website demo login                                                                               | To show login page          |             |        |
| 2  | Type demo to input text username_field.  Type mode to input password password_field.  Submit to login | Welcome Page Should Be Open |             |        |
