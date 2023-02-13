# Katalon SAP GUI Client sample project

## Prerequisites:

- Katalon Studio v7+
- WinAppDriver 1.1+
- SAP Scripting Tracker: https://tracker.stschnell.de/
- Enabling SAP Scripting mode: https://help.sap.com/viewer/8ecea00c1f854fd0a433c4aef5da1ea2/Cloud/en-US/001675913cc54719930aa8197478dcde.html

### Login

Open Profiles/default and change the username and password to your SAP account.

## How to record test script using Scripting Tracker

- Create new test case and copy the script content from Common/TestCaseTemplate
- Start SAPLogon and login
- Start Scripting Tracker and start recording
- Stop recording then copy and paste the content from Scripting Tracker into the test case script

## Videos tutorial
- Recording script with Scripting Tracker: Videos/Record test script tutorial.mp4

## Locator strategy
- findById
- findByName (https://blogs.sap.com/2017/04/12/how-to-combine-sap-gui-scripting-and-selenium-webdriver#comment-418401)

## Troubleshoot errors
```
com.jacob.com.ComFailException: Can't co-create object
```

Solution:
- Download new JVM/JRE 1.8 32 bit
- Update the above JRE for the project by following this guide: [https://docs.katalon.com/katalon-studio/how-to-guides/set-new-default-JRE.html](https://docs.katalon.com/docs/get-started/set-up-your-workspace/katalon-studio-preferences/set-a-new-default-jre-for-test-projects-in-katalon-studio)
