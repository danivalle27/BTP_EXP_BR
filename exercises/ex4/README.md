
# (Optional) Exercise 4 - Test Data

In this optional exercise, you will explore advanced features of Tricentis Test Automation (TTA) that help improve test reusability and maintainability. You’ll learn how to create Test Data Sets to store, update, and dynamically use data in the cloud. These advanced capabilities will help you reduce test maintenance and streamline large-scale automation scenarios.



## Creation of Test Data Set

If you want to keep your data in cloud and you need to make periodic/regular update of those data using Automation, TTA have the inbuilt feature called Test Data set.

Get your test data into Tricentis Test Automation by SAP, you have 2 options
1.Create your test data manually 
2.Upload a test data file

**Create test data manually**

To add a small data sample for experimenting or debugging, follow these steps:

1.Go to  Prepare > Test data<br>![](/exercises/ex4/images/CALM_DS_01.png)
2.Click Create data set.Data set & Columns names should be business relevant <br>![](/exercises/ex4/images/CALM_DS_03.png)
3.In the subsequent dialog, define the name of the data set and its first column. Then, select Create.<br>![](/exercises/ex4/images/CALM_DS_04.png)

4.Data set is created with first column, add the columns as per the requirement
Use the edit options to update your data set. For example, add cell values or more columns/rows.<br>![](/exercises/ex4/images/CALM_DS_05.png)<br>![](/exercises/ex4/images/CALM_DS_06.png)


To use test data in a test case, you need to link the two:

You can directly enter these values by using the syntax : **{TDM[Subset][ColumnName]}
**
And that's it! Your test data is now linked to this particular test action.<br>![](/exercises/ex4/images/CALM_DS_11.png)

Repeat the same process for all the values you want to flow from Test Data Set ( Cloud Storage)
<br>![](/exercises/ex4/images/CALM_DS_12.png)

## Summary

You’ve now explored the advanced capabilities of Tricentis Test Automation for SAP, learning how to create Test Data Sets for dynamic, cloud-based data handling. By using these features, you can make your automated tests more scalable, adaptable, and easier to maintain.

# Congratulation to finish all exercises!
