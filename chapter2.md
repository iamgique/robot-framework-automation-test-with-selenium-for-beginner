#Chapter 2
##Structure of Robot Framework

```
#Structure of Robot Framework
*** Settings ***
*** Variables ***
*** Keywords ***
*** Test Cases ***
```

###*** Settings ***
In part of Settings to keep Keywords of Library. Which Library like a Dictionary classified 3 part. Standard, External, Other

![Libraries Standard](/images/libraries-standard.png)

![Libraries External](/images/libraries-external.png)

![Libraries Other](/images/libraries-other.png)

**Library** import library.

**Resource** Include other file.

**Documentation** Description of this robot.

**Suite Setup** The first to do when this robot working.

**Suite Teardown** The last to do before end of robot working.

**Test Setup** The first to do when test case working.

**Test Teardown** The last to do before end of test case working.

**Test Template** Template for test case.

You can learn more at [robotframework](http://robotframework.org/#libraries).

###*** Variables ***
**Eg.**
```
${TEST_VARIABLE}         Welcome to Robot Framework Automation Test with Selenium for beginner class.
```
${TEST_VARIABLE} is a **variable**.
"Welcome to Robot Framework Automation Test with Selenium for beginner class." is a **value**.

**Eg2.**
```
${TEST_VARIABLE_A}         www.google.com
${TEST URL}      http://${TEST_VARIABLE_A}/
```
${TEST_VARIABLE_A} is a **variable**.
${TEST URL} is a **variable** and in Robot Framework variable can space.
"http://${TEST_VARIABLE_A}/" is a **value**.
${TEST URL} = http://www.google.com/

###*** Keywords ***
Keywords like a function in programming language.
**Eg.**
```
Test Keywords
    Click Button    ok_button
```
**Eg2.**
```
Test Keywords2
    [Arguments]    ${param}
    Input Text    field_name    ${param}
```
###*** Test Cases ***
```
Name Test Case
    Open Browser To Login Page
    Input Text    username_field    username
    Input Text    password_field    password
    Click Button    ok_button
    [Teardown]    Close Browser
```

##Command for run Robot Framework
```
Command:
robot ... (Robot 3.0 or more)
pybot ... (Robot 2.9 or earlier)
robot --help (for more information)

pybot login_tests
pybot login_tests/valid_login.robot
pybot login_tests/invalid_login.robot
pybot --test InvalidUserName --loglevel DEBUG login_tests

pybot --variable BROWSER:Chrome login_tests
pybot --variable BROWSER:IE login_tests
```
