# Exercises

## Exercise 1 - Create an automated test case with Tosca Cloud / SAP ECT

In this exercise, you will learn how to create and record an automated test case using Tricentis Tosca Cloud / SAP ECT Cloud. If Cloud ALM is available, we will start with it. Otherwise, skip to the next [step 1.3](https://github.com/danivalle27/BTP_EXP_BR/edit/main/exercises/ex1/README.md#exercise-13---initial-setup-of-the-automated-test-case).

## Exercise 1.1 - Creating a test case in SAP Cloud ALM 

1. Click on tab **Implementation** and on tile **Test Preparation**. It might be on the right side of the screen, slightly different from the picture.
<br>![](/exercises/ex1/images/CALM_Imp_TestPrep.png)
  
2.	Select a Project if available (Tricentis SAP BTP Exp or Implementation). Press the button "Create"
<br>![](/exercises/ex1/images/CALM_Create_TC.png)

3.  To create a new test case, enter on the side panel the following values:
    <br>**Type:** Automtated
    <br>**Automation Provider:** TTA_for_SAP (or ECT if available)
    <br>**Title:** ###-Test Case 1     *(replace the ### with your user number or name)*
    <br>**Project:** Tricentis SAP BTP Exp
    <br>**Scope:** whichever is available
    <br>**Solution Process:** whichever is available
    <br>**Country/Region:** whichever is available
<br>![](/exercises/ex1/images/CALM_Create_TC_save.png)

4.   IF Cloud ALM is available AND INTEGRATED with TTA/ECT/Tosca: The test case is now created on Cloud ALM side, as well as on ECT/TTA side. Jump to TTA by **clicking on the test case name** in the context area.
<br>![](/exercises/ex1/images/CALM_link_TTA.png)


## Exercise 1.2 Tosca Cloud / SAP ECT Cloud / Launcher 

If CloudALM is not available, here are the Tosca Cloud settings. If it is, skip to Launcher setup.

[Documentation can be found here](https://docs.tricentis.com/tosca-cloud/en-us/content/admin_guide/downloads_and_installations.htm)

[Cloud minimum system requirements](https://documentation.tricentis.com/tricentis_cloud/en/content/admin_guide/system_requirements.htm) 

### License

Option 1 - [request your own trial](https://www.tricentis.com/software-testing-tool-trial-demo/trial-tosca)
Make sure to add a valid email that you have access during the class. Check your email for confirmation.

Option 2 - join an existing instance.
https://sapbtpexperience.my.tricentis.com/_portal/space/Default/home 

Provide your email during the class for access.

## Install the Launcher (browser you are running Tosca Cloud/SAP ECT/TTA)

1. Before starting any automation, the Launcher needs to be installed. For this press the **Downloads** button at the upper right corner and click then on Download.
   <br>![](/exercises/ex1/images/Launcher_Setup.png)
3. Run the Launcher Setup from Downloads and wait for it to completed. If it is already installed, please use the update option. Close the success message.

## Exercise 1.3 - The Automated test case

1. Open the following    <br>![EXERCISE 1](https://github.com/danivalle27/BTP_EXP_BR/blob/main/exercises/SAPBTP_EX1.docx) - CLICK ON VIEW RAW

2. If your CloudALM integration worked, skip to step 1.5


## Summary

You have successfully created your first automated test case from SAP Cloud ALM with Tricentis Test Automation. By completing this exercise, you learned how the  tools works together, capture application elements, define reusable modules, and automate a business process from login to quotation creation.

Continue now to - [Exercise 2 - Best Practices for Automation](../ex2/README.md)
