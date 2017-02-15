#Robot Framework Automation Test with Selenium for beginner

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

  Look up "Path" then click edit put **C:\Python27;** at the last character and then put **C:\Python27\Scripts;**
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
