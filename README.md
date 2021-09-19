<!-- # Pandas_Visualization -->
# pandas 
      is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool,
      built on top of the Python programming language.

# install pandas (basic, if path is not set yet)
py -m pip install pandas
# or set PATH to use pip:
setx PATH "%PATH%;C:\<path\to\python\directory\>\Scripts"
pip install pandas
# if "connection error: [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed" [!]:
py -m pip install --trusted-host pypi.python.org pip pandas
# if PermissionError: [WinError 5] Access is denied
py -m pip install --user pandas
# or via creating a virtual environment venv:
py -m venv c:\path\to\new\environment
# then execute:
c:\path\to\new\environment\Scripts\activate.bat
