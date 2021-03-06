#Chapter 1

#Welcome to Robot Framework Automation Test with Selenium for beginner class

###Robot Framework is software open source, for Acceptance Testing and ATDD (Acceptance Test-Driven Development).
###Robot Framework implemented with Python(both Python2 and Python3) and supports also Jython (JVM), IronPython (.NET) and PyPy.

###Python installation
On most UNIX-like systems such as Linux and OS X you have Python installed by default.<br />
If you are on Windows or otherwise need to install Python yourself.<br />

###Why we use Python 2.7
The last Python 2 release is **Python 2.7** that was released in **2010** and will be **supported until 2020**.<br />
Python 2 and Python 3 are mostly the same language, but they are not fully compatible with each others.<br />
The main difference is that in **Python 3 all strings are Unicode** while in **Python 2 strings are bytes by default**, but there are also several other backwards incompatible changes.<br />

###Robot Framework 3.0
Robot Framework 3.0 is the first Robot Framework version to support Python 3.<br />
Robot Framework 3.0 supports Python 2.6, 2.7, 3.3 and newer.<br />

###Robot Framework documentation
###High-level architecture

![install Package](/images/high-level-architecture.png)<br />

The test data is in simple, easy-to-edit tabular format.<br />
When Robot Framework is started, it processes the test data, executes test cases and generates logs and reports.<br />
The core framework does not know anything about the target under test, and the interaction with it is handled by test libraries.<br />
Libraries can either use application interfaces directly or use lower level test tools as drivers.<br />

Following screenshots show examples of the created reports and logs.<br />
![install Package](/images/testcase.png)

[Robot Framework documentation](http://robotframework.org/robotframework/)

[Robot Framework BuiltIn](http://robotframework.org/robotframework/3.0.2/libraries/BuiltIn.html)
