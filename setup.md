#Robot Framework Automation Test with Selenium for beginner

#SETUP
##Install Python 2.7
###Download Python: [download Python](https://www.python.org/ftp/python/2.7.8/python-2.7.8.msi)

```
Command:
cd C:\Python27
C:\Python27>python
Python 2.7.8 (default, Jun 30 2014, 16:03:49) [MSC v.1500 32 bit (Intel)] on win
32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

###Download get-pip.py: [download pip](https://bootstrap.pypa.io/get-pip.py)
**pip is the preferred installer program.**

Go to path download **get-pip.py**. Then run **python get-pip.py**. This will install pip.

```
Command:
C:\user\guest>python get-pip.py
C:\user\guest>cd C:\python27\Scripts
C:\python27\Scripts>pip freeze
antiorm==1.1.1
enum34==1.0
requests==2.3.0
virtualenv==1.11.6
```

##Set Environment Variables
Right click at **My Computer > Properties > Advanced system settings > Environment Variables**
And then look at System variables click **New..**
```
Variable name:  PYTHON_HOME
Variable value: C:\Python27
Click OK
```
![install Package](/images/1-system-variable.png)

  For **windows10** look up **Path** then click edit put **C:\Python27;** at the last character and then put **C:\Python27\Scripts;** other **windows**
  For other **windows** look up **Path** then click edit put **;%PYTHON_HOME%\;%PYTHON_HOME%\Scripts**
  Click OK

![install Package](/images/2-system-variable.png)

**Verify a successful installation**

```
Command:
C:\user\guest>python
C:\Python27>python
Python 2.7.8 (default, Jun 30 2014, 16:03:49) [MSC v.1500 32 bit (Intel)] on win
32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

```
C:\user\guest>pip freeze
antiorm==1.1.1
enum34==1.0
requests==2.3.0
virtualenv==1.11.6
```

###Documentation: [Document](https://github.com/BurntSushi/nfldb/wiki/Python-&-pip-Windows-installation)

-----------------

##Install Text editor
###Download ATOM: [Download ATOM](https://atom.io/)
After installed go to **file > settings** click Install then type robot and type terminal follow figure.

![install Package](/images/2-install-package.png)

![install Package](/images/3-install-package.png)

-----------------

##Install Robot Framework with pip
```
Command:
pip install robotframework
```

```
# Upgrade to the latest version
pip install --upgrade robotframework

# Install a specific version
pip install robotframework==2.9.2
```

##Install Robot Framework Selenium2library with pip
```
Command:
pip install robotframework-selenium2library
pip freeze
appdirs==1.4.0
decorator==4.0.11
packaging==16.8
pyparsing==2.1.10
robotframework==3.0.2
robotframework-selenium2library==1.8.0
selenium==3.0.2
six==1.10.0
```

###Download Chrome driver [Download Chrome driver](https://chromedriver.storage.googleapis.com/index.html?path=2.27/)
Extract Zip then move **chromedriver.exe** to **C:\Python27\Scripts**

##End of Setup
