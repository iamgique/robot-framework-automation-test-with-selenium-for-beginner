#Chapter 1
##Robot Framework documentation
###High-level architecture
Robot Framework is a generic, application and technology independent framework.

![install Package](/images/high-level-architecture.png)

The test data is in simple, easy-to-edit tabular format. When Robot Framework is started, it processes the test data, executes test cases and generates logs and reports. The core framework does not know anything about the target under test, and the interaction with it is handled by test libraries. Libraries can either use application interfaces directly or use lower level test tools as drivers.

Following screenshots show examples of the created reports and logs.
![install Package](/images/testcase.png)

[Robot Framework documentation](http://robotframework.org/robotframework/)

[Robot Framework BuiltIn](http://robotframework.org/robotframework/3.0.2/libraries/BuiltIn.html)

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
