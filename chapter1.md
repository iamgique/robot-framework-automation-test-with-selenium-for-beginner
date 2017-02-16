#Chapter 1
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
##Robot Framework documentation
[Robot Framework documentation](http://robotframework.org/robotframework/)
[Robot Framework BuiltIn](http://robotframework.org/robotframework/3.0.2/libraries/BuiltIn.html)
