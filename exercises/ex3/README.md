# Exercise 3 - Create another step recording and handover data

In this exercise, you will extend your automation by creating a new recording for the Sales Order creation process using a Sales Quotation as reference. You’ll duplicate existing steps to save effort, structure them into a new folder, and modify values to match the new process. Finally, you’ll learn how to handover data—specifically the quotation number—between test cases to enable seamless end-to-end test automation.

## Exercise 3.1 Record process "Creating a Sales Order with Sales Quotation Reference"

1.Create a Test step folder and name it as "Create Sales Order" under Process.<br>![](/exercises/ex4/images/CALM_SO_01.png)
2. Duplicate the **Search for the Application in Fiori Home Page** from Create Sales Quotation folder<br>![](/exercises/ex4/images/CALM_SO_02.png)
3. Click on the  (3 dots) and select **Duplicate** option <br>![](/exercises/ex4/images/CALM_SO_03.png)
4. Hover over the duplicated step and click on the icon with the six dots and move the test step to Create Sales Order **<br>![](/exercises/ex4/images/CALM_SO_04.png)
5. The folders **Create Sales Quotation** and **Create Sales Order** should appear below the folder **Process**
6. Change value in the **Search in Apps** text box to *Manage Sales Orders* <br>![](/exercises/ex4/images/CALM_SO_05.png)
7. Capture the Search results screen <br>![](/exercises/ex4/images/CALM_SO_06.png)
8. Add the step to the Create Sales Order folder <br>![](/exercises/ex4/images/CALM_SO_07.png)
9. In Manage Sales Order screen, Expand the Create with reference drop down <br>![](/exercises/ex4/images/CALM_SO_08.png)
10. Capture this screen by using Select on Screen option in the Scan window <br>![](/exercises/ex4/images/CALM_SO_09.png)
11. Search for the module and jump to the module. Module will open in new tab <br>![](/exercises/ex4/images/CALM_SO_10.png)
12. Click on the icon with the six dots and move the Create with Reference button to the top.<br>![](/exercises/ex4/images/CALM_SO_11.png)<br>![](/exercises/ex4/images/CALM_SO_12.png)
13. Go back to the Test case tab and add this module to the Create Sales Order folder <br>![](/exercises/ex4/images/CALM_SO_13.png)
14: Pass the Values in test step as below <br>![](/exercises/ex4/images/CALM_SO_14.png)
15. Capture the next screen <br>![](/exercises/ex4/images/CALM_SO_14.png)
16. Search & Add this module to the folder. Here we are going to use the Sales Quotation buffered in the previous process
      In last step of previous exercise we stored the Sales Quotation value in “QuotationID”
      {B[Buffer Name]}- is the syntax to re-use the stored buffered in the test step
      These buffers are temporarily stored for the session across the workspace.
      Test step should appear as below
      In Sales order type text drop down box use the option available in Value column of the test step and select the value as below.<br>![](/exercises/ex4/images/CALM_SO_15.png)
17. Capture the next screen





## Exercise 3.2 Handover Quotation Number from Quotation Creation to Sales Order Creation


## Summary

You’ve now created a new automated recording for Sales Order creation with Quotation Reference and learned how to reuse and adapt existing steps efficiently. By handing over the quotation number dynamically between test cases, you’ve established a data-driven link that supports end-to-end business process automation across multiple test scenarios.

Continue to - [Exercise 4 - (Optional) Exercise 4 - Advanced features of TTA](../ex4/README.md)
