# CSVUtility
This is a CSV reader utility tool, The purpose of this utility is to read the Order-Details from CSV format file, and this utility output creates two 'CSV' files and both the csv files are generated according to the business rules.

The structure of input csv file is as follows

Each line contains a single record with the following columns, in order:

Id of the order placed
Area where the order was delivered
Name of the product
Quantity of the product delivered in that order
Brand of the ordered product
The structure of output csv files is as follows

0_input_file_name - In the first column, list the product Name. The second column should contain the average quantity of the product purchased per order.

1_input_file_name - In the first column, list the product Name. The second column should be the most popular Brand for that product. Most popular is defined as the brand with the most total orders for the item, not the quantity purchased. If two or more brands have the same popularity for a product, include any one.

How to execute or setup development enviornment
Visual Studio 2017 or later
This is the more straightforward way to get started:

Open CSVUtility.sln file with Visual Studio 2017 or later version. Select CSVUtilityUI project and right-click on it and choose Set as StartUp project.

Build the complete solution and press F5 to run application.

![204104265-c9b2cc23-76b7-48be-9081-eefc5710637d](https://user-images.githubusercontent.com/62908191/204104820-a6c35afd-57b6-4170-9583-9f5478a167f4.png)


Run Application with .EXE file
After the build process is completed, the executable file will be generated inside the release or debug folders.

This executable file can be run from Windows File Explorer or from any command line tool e.g. WindowsCommandPrompt(CMD), Windows Powershell etc.

![204104549-00fcc809-d35d-43b3-9c5f-9345923efc51](https://user-images.githubusercontent.com/62908191/204104833-ea19f9fd-28f4-425a-9800-bd0442a62b23.png)
