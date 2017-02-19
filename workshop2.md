#Workshop 2
###Login Website

**This workshop like a workshop 1 but this workshop difference**<br />

**Workshop 2** run at your local by python server.<br />
This workshop use Library and keywords. eg. **Suite Setup, Suite Teardown, Test Setup, Test Template**.<br />
This workshop use Variables.<br />
This workshop use **gherkin** style for test case.<br />

**Task**<br />
1.Start Server with Python.<br />
2.Run robot with valid_login.robot<br />
3.Run robot with invalid_login.robot<br />
4.Run robot with gherkin_login.robot<br />
5.Run robot all file<br />
6.Reports<br />

**Valid Login**<br />
valid_login.robot<br />

| No | Test Procedure                                                                                        | Expected Result             | Test Result | Remark |
|----|-------------------------------------------------------------------------------------------------------|-----------------------------|-------------|--------|
| 1  | Open website demo login                                                                               | To show login page          |             |        |
| 2  | Type demo to input text username_field.  Type mode to input password password_field.  Submit to login | Welcome Page Should Be Open |             |        |


**invalid Login**<br />
invalid_login.robot<br />

| No | Test Procedure                                                                                          | Expected Result                                      | Test Result | Remark |
|----|---------------------------------------------------------------------------------------------------------|------------------------------------------------------|-------------|--------|
| 1  | Open website demo login                                                                                 | To show login page                                   |             |        |
| 2  | Type invalid to input text username_field. Type mode to input password password_field. Submit to login  | Location Should Be error. Title Should Be,Error Page |             |        |
| 3  | Type demo to input text username_field. Type whatever to input password password_field. Submit to login | Location Should Be error. Title Should Be,Error Page |             |        |
| 4  | Type "" to input text username_field. Type mode to input password password_field. Submit to login       | Location Should Be error. Title Should Be,Error Page |             |        |
| 5  | Type demo to input text username_field. Type "" to input password password_field. Submit to login       | Location Should Be error. Title Should Be,Error Page |             |        |
| 6  | Type "" to input text username_field. Type "" to input password password_field. Submit to login         | Location Should Be error. Title Should Be,Error Page |             |        |

**Valid Login with gherkin style**<br />
gherkin_login.robot<br />

| No | Test Procedure                                                                                        | Expected Result             | Test Result | Remark |
|----|-------------------------------------------------------------------------------------------------------|-----------------------------|-------------|--------|
| 1  | Open website demo login                                                                               | To show login page          |             |        |
| 2  | Type demo to input text username_field.  Type mode to input password password_field.  Submit to login | Welcome Page Should Be Open |             |        |
