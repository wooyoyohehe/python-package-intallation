# How to install pandas and mysql-connector by pip
## Why pip?
Pip is the package installer for Python. You can use it to install packages from the Python Package Index and other indexes. Also, it runs well both on Windows and macOS. Last but not least, it is an easier way to install packages, not only pandas and mysql-connector, but also the package you may use in the future.
## Install pip
  - Follow the instruction in [official intallation doc](https://pip.pypa.io/en/stable/installation/) to install
## Verify pip
  - Open the terminal on macOS or command line on Windows
  - Type in 'python' and press enter
  ```
  pip --version     # Python2.x version uses this command
  pip3 --version    # Python3.x version uses this command
  ```

## Install Pandas
Open the terminal on macOS or command line on Windows and type in the following code:
```
pip install pandas
```
## Verify Pandas
  - Open the terminal on macOS or command line on Windows
  - Type in 'python' and press enter
  - type in the following code one by one:
    ```
    import pandas
    pandas.__version__
    ```
  - If you get the version number, you have succeeded.
## Install Python mql-connector
Open the terminal on macOS or command line on Windows and type in the following code:
```
python -m pip install mysql-connector
```
## Verify mysql-connector
  - Open the terminal on macOS or command line on Windows
  - Type in 'python' and press enter
  - type in the following code:
    ```
    import mysql.connector
    ```
  - If there is no error, you have succeeded.
