# Exercise 3 - Create another step recording and handover data

In this exercise, you will extend your automation by creating a new recording for the Sales Order creation process using a Sales Quotation as reference. You’ll duplicate existing steps to save effort, structure them into a new folder, and modify values to match the new process. Finally, you’ll learn how to handover data—specifically the quotation number—between test cases to enable seamless end-to-end test automation.

## Exercise 3.1 Record process "Creating a Sales Order with Sales Quotation Reference"

1.Create a Test step folder and name it as "Create Sales Order" under Process.
2. Duplicate the **Search for the Application in Fiori Home Page** from Create Sales Quotation folder
3. Click on the  (3 dots) and select Duplicate option
4. Select option **Duplicate**
5. Create a folder and name it as *Create Sales Order*
6. Hover over the duplicated step and click on the icon with the six dots and move the test step to Create Sales Order
7. The folders **Create Sales Quotation** and **Create Sales Order** should appear below the folder **Process**
8. Change value in the **Search in Apps** text box to *Manage Sales Orders*


## Exercise 3.2 Handover Quotation Number from Quotation Creation to Sales Order Creation


## Summary

You’ve now created a new automated recording for Sales Order creation with Quotation Reference and learned how to reuse and adapt existing steps efficiently. By handing over the quotation number dynamically between test cases, you’ve established a data-driven link that supports end-to-end business process automation across multiple test scenarios.

Continue to - [Exercise 4 - (Optional) Exercise 4 - Advanced features of TTA](../ex4/README.md)
