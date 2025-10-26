# Exercise 1 - Creating an automated test case with TTA from SAP Cloud ALM

In this exercise, we will create a test case in SAP Cloud ALM, that is then recorded with Tricentis Test Automation tool.

## Exercise 1.1 - Creating an automated test case in SAP Cloud ALM and enter TTA

1. Click on tab **Implementation** and on tile **Test Preparation**.
<br>![](/exercises/ex1/images/CALM_Imp_TestPrep.png)
  

2.	Check, if Project **TechEd Transformation Project** is selected. Press than button "Create"
<br>![](/exercises/ex1/images/CALM_Create_TC.png)

3.  To create a new test case, enter on the side panel the following values:
    <br>**Type:** Automtated
    <br>**Automation Provider:** TTA_for_SAP
    <br>**Title:** ###-Sales Order Processing for Non-Stock Material (2ET)     *(replace the ### with your user number)*
    <br>**Project:** TechEd Transformation Project
    <br>**Scope:** BTM163 - Cloud ALM & TTA
    <br>**Solution Process:** Sales Order Processing for Non-Stock Material (2ET)
    <br>**Country/Region:** Germany
<br>![](/exercises/ex1/images/CALM_Create_TC_save.png)

4.   The test case is now created on Cloud ALM side, as well as on TTA side. Jump to TTA by **clicking on the test case name** in the context area.
<br>![](/exercises/ex1/images/CALM_link_TTA.png)

## Exercise 1.2 - Install the Launcher

1. Before starting any recording in TTA, the Launcher needs to be installed. For this press the **Download** button at the upper right corner and click then on Download.
   <br>![](/exercises/ex1/images/Launcher_Setup.png)
3. Run the Launcher Setup and wait for it to completed. Close the success message

## Exercise 1.3 - Initial Setup of the automated test case

1. Once TTA URL Launched, create a new parameter. It will define the browser for execution.
    <br>**Name:** Browser
    <br>**Data Type:** String
    <br>**Value:** Chrome
<br>![](/exercises/ex1/images/TTA_Create_Parameter.png)

2.	Create 3 Test step folders
    <br> - Precondition   *(Contains login flows and prerequisites)*
  	<br> - Process        *(Contains the actual business flow, Validation flow)*
  	<br> - Postcondition  *(Contains post validation steps (Ex: Logout & Close browser))*
<br>![](/exercises/ex1/images/TTA_Create_Folders.png)

## Exercise 1.4 - Create new module for the Login to S/4HANA system

1. Click to open [SAP S/4HANA system](https://btm163-7rq549xc.eu10-004.alm.cloud.sap/launchpad#Shell-home) and follow the steps below:
   # add infos here

2. Go back to TTA and click on tab **Modules** in the left panel and then **Create module**
   <br>![](/exercises/ex1/images/TTA_Create_Module.png)

3. After clicking Create Module button, below pop-up appears. Select the Web Application from the list (This screen is to select the type of application (Web, Desktop, etc…))
    <br>![](/exercises/ex1/images/TTA_Scan_App_Popup.png)

4. It might happen, that the Tricentis Launcher is starting a setup. If this takes longer than 2 minutes, just let us know. The XScan application as shown in the below screenshot appears. Select the browser window with the opened S/4HANA system and press button **Scan**.
   <br>![](/exercises/ex1/images/TTA_XScan_App_Select.png)

5. Capture the fields *User Name*, *Password* and the button *Log On*. Mark the title of the Log On button more dynamic and unique and rename the module accordingly so that you can easily find it later in the module area (e.g. *S/4HANA Fiori Login*)
   <br>![](/exercises/ex1/images/TTA_Capture_Login&Rename.png)

6. Close the scanning.


## Summary

You've now created your first automated test case with SAP Cloud ALM and Tricentis Test Automation tool.

Continue to - [Exercise 2 - Design the Test Case in Tricentis Test Automation](../ex2/README.md)
