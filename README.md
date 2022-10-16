# Web-Automation-Using-Robotframework

## Python-Robot-Framework-POM-Baynna.com
Getting & Setting up the project


#### Heading 4
Clone the project at any location
Go to cloned project folder
Install all the dependencies by running the following command
py -m pip install -r requirements.txt

######### Heading 4
Run Single Test Case:
robot .\folder name\file name in this folder.robot

Run Suite:
robot .\TestCases

Run Test Cases To Generate Allure Result
Allure Report

$ py -m pip install allure-robotframework
robot --listener allure_robotframework .\TestCases\
allure serve .\output\allure\
