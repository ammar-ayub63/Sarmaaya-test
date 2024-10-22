# Sarmaaya-test

Here are the prerequisites to run the TestSuite.robot:

Download and install Python:

Here is the link to download python: https://www.python.org/downloads/

1. Download the latest version of Python.
2. Run the downloaded executable file.
3. Tick the Add python.exe to PATH.
4. When python is downloaded and installed, go to the command prompt and run: python --version. The python version should appear successfully.

Install the robot framework:

1. Open the command prompt.
2. Run the command: pip install robotframework. Robot will be installed successfully.

Install the selenium library:

1. Open the command prompt.
2. Run the command: pip install robotframework-seleniumlibrary. The selenium library will be installed successfully.
3. Open this project in any IDE of your choice. (VSCode and PyCharm are good options)

Open the terminal. Make sure that this project is opened in the terminal.

To run the complete test suite, run this command in the terminal: robot .\TestSuite.robot. The complete test suite will be executed successfully and a report will be auto-generated in the project folder.

FYI: Make sure that you have the latest chrome version installed on your laptop i.e. chrome version 130. The chromedriver used in the project only supports chrome version 130. It won't run the test if you're using an older version of chrome. Thanks!
