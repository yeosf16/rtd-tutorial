Using Workspace
===============

.. _quick-overview-1:

Quick Overview
--------------

Workspace is a designer that allows the user to create projects and
workflow on their own device. The created workflow can also be run
locally to be tested.

Run and Open Workspace
~~~~~~~~~~~~~~~~~~~~~~

1. Click the Workspace icon.

..

   |image28|

2. A window will appear, click “Start”. **(This window should remain
   open when using Workspace)**

..

   |image29|

3. A browser page will be opened automatically.

..

   |image30|

Functions
---------

Web
~~~

   A group of functions that will perform browser actions such as
   accessing a website and clicking on a web element.

Browser Back
^^^^^^^^^^^^

   |image31|

   Function: Go to the previous browser page

Browser Forward
^^^^^^^^^^^^^^^

   |image32|

   Function: Go forward one browser page

Click By XPath
^^^^^^^^^^^^^^

   |image33|

   Function: Click on a web element using XPath

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Click Type             | Choose left click, right click, or double   |
|                        | click.                                      |
+------------------------+---------------------------------------------+
| XPATH                  | Put the xPath of the web element.           |
+------------------------+---------------------------------------------+

Click Web Element
^^^^^^^^^^^^^^^^^

   |image34|

   Function: Click on a web element.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Element                | Choose the correct Child, Child &           |
|                        | Grandchild for the xPath.                   |
+------------------------+---------------------------------------------+
| Element Type           | Choose the type of web element.             |
+------------------------+---------------------------------------------+
| Search By              | Choose what xPath you are copying.          |
+------------------------+---------------------------------------------+
| Element Name To Match  | Put the name to match with the “Search By”. |
+------------------------+---------------------------------------------+
| Nth Match Element      | Put the element after the element name.     |
+------------------------+---------------------------------------------+

Double Click Web Element
^^^^^^^^^^^^^^^^^^^^^^^^

   |image35|

   Function: To double-click on a web element

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Element                | Choose the correct Child, Child &           |
|                        | Grandchild for the xPath.                   |
+------------------------+---------------------------------------------+
| Element Type           | Choose the type of web element.             |
+------------------------+---------------------------------------------+
| Search By              | Choose what xPath you are copying.          |
+------------------------+---------------------------------------------+
| Element Name To Match  | Put the name to match with the “Search By”. |
+------------------------+---------------------------------------------+
| Nth Match Element      | Put the element after the element name.     |
+------------------------+---------------------------------------------+

Download To
^^^^^^^^^^^

   |image36|

   Function: Declare the path to store downloaded files instead of the
   default download folder

+------------------------+---------------------------------------------+
| **Parameter**          | Description                                 |
+------------------------+---------------------------------------------+
| Folder Location        | To put your folder location that you want   |
|                        | the file to download to.                    |
+------------------------+---------------------------------------------+

Email
^^^^^

   |image37|

   Function: Send an email using outlook website

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| To                     | The receiver of the email.                  |
+------------------------+---------------------------------------------+
| CC                     | The emails that will receive a cc of the    |
|                        | email.                                      |
+------------------------+---------------------------------------------+
| Subject                | The subject of the email.                   |
+------------------------+---------------------------------------------+
| Body                   | The body of the email.                      |
+------------------------+---------------------------------------------+

Read Web Element
^^^^^^^^^^^^^^^^

   |image38|

   Function: To read the text of the web element.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Element                | Choose the correct Child, Child &           |
|                        | Grandchild for the xPath.                   |
+------------------------+---------------------------------------------+
| Element Type           | Choose the type of web element.             |
+------------------------+---------------------------------------------+
| Search By              | Choose what xPath you are copying.          |
+------------------------+---------------------------------------------+
| Element Name To Match  | Put the name to match with the “Search By”. |
+------------------------+---------------------------------------------+
| Nth Match Element      | Put the element after the element name.     |
+------------------------+---------------------------------------------+
| Variable to store      | The variable that will store the text.      |
+------------------------+---------------------------------------------+

Read XPath
^^^^^^^^^^

   |image39|

   Function: Read the text on specific XPATH

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| XPATH                  | The XPath of the element.                   |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the text.             |
+------------------------+---------------------------------------------+

Refresh Web Element
^^^^^^^^^^^^^^^^^^^

   |image40|

   Function: To refresh the website, same as pressing the refresh
   function (F5)

Save Table
^^^^^^^^^^

   |image41|

   Function: Save the html table data to csv file.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Table XPATH            | The XPath of the html table.                |
+------------------------+---------------------------------------------+
| CSV Filename           | The file path of the csv file.              |
+------------------------+---------------------------------------------+

Set Web Wait Timeout
^^^^^^^^^^^^^^^^^^^^

   |image42|

   Function: Set the wait timeout for the website

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Second to wait         | The number of seconds to wait before        |
|                        | timeout.                                    |
+------------------------+---------------------------------------------+

Type On Element
^^^^^^^^^^^^^^^

   |image43|

   Function: To type text on a web element

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Element Name           | The name of the element to be typed on.     |
+------------------------+---------------------------------------------+
| Text                   | The text to be typed .                      |
+------------------------+---------------------------------------------+
| Followed by ENTER      | Should the text be followed by enter key.   |
+------------------------+---------------------------------------------+

Type Web Element
^^^^^^^^^^^^^^^^

   |image44|

   Function: To type text on a web element

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Element                | Choose the correct Child, Child &           |
|                        | Grandchild for the xPath.                   |
+------------------------+---------------------------------------------+
| Element Type           | Choose the type of web element.             |
+------------------------+---------------------------------------------+
| Search By              | Choose what xPath you are copying.          |
+------------------------+---------------------------------------------+
| Element Name To Match  | Put the name to match with the “Search By”. |
+------------------------+---------------------------------------------+
| Nth Match Element      | Put the element after the element name.     |
+------------------------+---------------------------------------------+
| Text                   | The text to be typed.                       |
+------------------------+---------------------------------------------+

Upload To
^^^^^^^^^

   |image45|

   Function: Upload file to the web

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| DOM of upload element  | The DOM of the upload element in the        |
|                        | website.                                    |
+------------------------+---------------------------------------------+
| FIlename               | The filepath of the file to be uploaded.    |
+------------------------+---------------------------------------------+

.. _web-1:

Web
^^^

   |image46|

   Function: Open a website

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| URL                    | The url of the website to be opened.        |
+------------------------+---------------------------------------------+

Web API
^^^^^^^

   |image47|

   Function:

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Login URL              |                                             |
+------------------------+---------------------------------------------+
| Username               |                                             |
+------------------------+---------------------------------------------+
| Password               |                                             |
+------------------------+---------------------------------------------+
| WT Token Name          |                                             |
+------------------------+---------------------------------------------+
| Web API URL            |                                             |
+------------------------+---------------------------------------------+
| Output                 |                                             |
+------------------------+---------------------------------------------+

Mouse & Keyboard
~~~~~~~~~~~~~~~~

   A group of functions that will perform mouse and keyboard actions
   such as mouse clicking and keyboard typing.

Click UI
^^^^^^^^

   |image48|

   Function: Click the UI at specific location

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Click Type             | Select whether to left click, right click   |
|                        | or double-click.                            |
+------------------------+---------------------------------------------+
| X coordinate           | X coordinate of the target on screen.       |
+------------------------+---------------------------------------------+
| Y coordinate           | Y coordinate of the target on screen.       |
+------------------------+---------------------------------------------+

Click UI By Image
^^^^^^^^^^^^^^^^^

   |image49|

   Function: Click the UI based on image

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Click Type             | Select whether to left click, right click   |
|                        | or double-click.                            |
+------------------------+---------------------------------------------+
| Image                  | The image of the UI to be clicked.          |
+------------------------+---------------------------------------------+

Close Application
^^^^^^^^^^^^^^^^^

   |image50|

   Function: To close the current window

Hover UI
^^^^^^^^

   |image51|

   Function: Hover the mouse over the UI at a specific location

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| X coordinate           | X coordinate of the target on screen.       |
+------------------------+---------------------------------------------+
| Y coordinate           | Y coordinate of the target on screen.       |
+------------------------+---------------------------------------------+

Hover UI By Image
^^^^^^^^^^^^^^^^^

   |image52|

   Function: Hover the mouse over the UI based on image

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Image                  | The image of the UI to be hover over.       |
+------------------------+---------------------------------------------+

Keyboard
^^^^^^^^

   |image53|

   Function: Input of keyboard special key.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Keys                   | A selection of special keystroke such as    |
|                        | spacebar and alt.                           |
+------------------------+---------------------------------------------+

Keyboard Input
^^^^^^^^^^^^^^

   |image54|

   Function: Input of text or combination of keystroke.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Input                  | The text that will be typed.                |
+------------------------+---------------------------------------------+

Keyboard Type Input
^^^^^^^^^^^^^^^^^^^

   |image55|

   Function: To input a sentence

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Text                   | The sentences of text to be input.          |
+------------------------+---------------------------------------------+

OCR - Click
^^^^^^^^^^^

   |image56|

   Function: Using OCR to click on a string of text

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Click Type             | Select whether to left click, right click   |
|                        | or double-click.                            |
+------------------------+---------------------------------------------+
| Search String On       | The string of text to be searched for using |
| Screen                 | OCR.                                        |
+------------------------+---------------------------------------------+

Open Application
^^^^^^^^^^^^^^^^

   |image57|

   Function: To open an application in the computer

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Application Name       | The name of the application to be opened.   |
+------------------------+---------------------------------------------+

Open File
^^^^^^^^^

   |image58|

   Function: To open a file of an application

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Application Name       | The name of the application.                |
+------------------------+---------------------------------------------+
| File Path              | The file path of the file.                  |
+------------------------+---------------------------------------------+

Save File
^^^^^^^^^

   |image59|

   Function: To save the file

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| File Name              | The name of the saved file.                 |
+------------------------+---------------------------------------------+

Set Focus
^^^^^^^^^

   |image60|

   Function: To modify an opened window

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Windows Name           | The name of the window.                     |
+------------------------+---------------------------------------------+
| Mode                   | Choose to restore, maximize or minimize the |
|                        | window.                                     |
+------------------------+---------------------------------------------+

Windows Run
^^^^^^^^^^^

   |image61|

   Function: To open the Run Window

Excel Interop
~~~~~~~~~~~~~

   A group of functions that will perform excel action with the excel
   being opened on the screen.

Close Work Sheet
^^^^^^^^^^^^^^^^

   |image62|

   Function: To close an opened worksheet

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel File             | The name of the excel file.                 |
+------------------------+---------------------------------------------+
| Sheet name             | The name of the worksheet.                  |
+------------------------+---------------------------------------------+
| Save                   | An option to save or not save the           |
|                        | worksheet.                                  |
+------------------------+---------------------------------------------+

Copy Data
^^^^^^^^^

   |image63|

   Function: To copy a range of data from one excel sheet to another

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Source Excel Filename  | The path of the source excel.               |
+------------------------+---------------------------------------------+
| Source Sheet           | The name of the source excel sheet.         |
+------------------------+---------------------------------------------+
| Cell Range             | The range of data to be copied.             |
+------------------------+---------------------------------------------+
| Target Excel FIlename  | The path of the target excel.               |
+------------------------+---------------------------------------------+
| Target SHeet           | The name of the target excel sheet.         |
+------------------------+---------------------------------------------+
| Starting Cell          | The first cell to start pasting the copied  |
|                        | data.                                       |
+------------------------+---------------------------------------------+

Copy Excel
^^^^^^^^^^

   |image64|

   Function: Copy the range of data from one excel sheet to another.
   (The file needs to be uploaded to the DD RPA workspace)

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Source File            | The name of the source file.                |
+------------------------+---------------------------------------------+
| Source Sheet           | The sheet name of the source excel file.    |
+------------------------+---------------------------------------------+
| Start Source           | The starting cell to copy the data.         |
+------------------------+---------------------------------------------+
| End Source             | The ending cell to copy the data.           |
+------------------------+---------------------------------------------+
| Destination File       | The name of the destination file.           |
+------------------------+---------------------------------------------+
| Destination Sheet      | The name of the destination excel file.     |
+------------------------+---------------------------------------------+
| Start Destination      | The starting cell to paste the data.        |
+------------------------+---------------------------------------------+
| End Destination        | The ending cell to paste the data.          |
+------------------------+---------------------------------------------+

Copy Excel Path
^^^^^^^^^^^^^^^

   |image65|

   Function: Copy a range of data from one excel sheet to another.
   (Using the file path of the excel file that is located in the device)

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Source File            | The name of the source file .               |
+------------------------+---------------------------------------------+
| Source Sheet           | The sheet name of the source excel file.    |
+------------------------+---------------------------------------------+
| Start Source           | The starting cell to copy the data.         |
+------------------------+---------------------------------------------+
| End Source             | The ending cell to copy the data.           |
+------------------------+---------------------------------------------+
| Destination File       | The name of the destination file.           |
+------------------------+---------------------------------------------+
| Destination Sheet      | The name of the destination excel file.     |
+------------------------+---------------------------------------------+
| Start Destination      | The starting cell to paste the data.        |
+------------------------+---------------------------------------------+
| End Destination        | The ending cell to paste the data.          |
+------------------------+---------------------------------------------+

Delete Excel Path
^^^^^^^^^^^^^^^^^

   |image66|

   Function: Delete data in an excel sheet

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| FileName               | The name of the excel file.                 |
+------------------------+---------------------------------------------+
| SHeet Name             | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Start Row-Column       | The first cell of data.                     |
+------------------------+---------------------------------------------+
| End Row-Column         | The last cell of data.                      |
+------------------------+---------------------------------------------+

Open Excel
^^^^^^^^^^

   |image67|

   Function: Open an excel file

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| File Path              | The file path of the excel file to be       |
|                        | opened.                                     |
+------------------------+---------------------------------------------+

Red Excel
^^^^^^^^^

   |image68|

   Function: To read a range of data into a data array

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel Filename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Range                  | The range of data to be read.               |
+------------------------+---------------------------------------------+
| Data Array             | The data array variable to store the data.  |
+------------------------+---------------------------------------------+

Read Excel Rows
^^^^^^^^^^^^^^^

   |image69|

   Function: Read a row of data into a variable

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Variable               | THe variable to store the data.             |
+------------------------+---------------------------------------------+
| File Name              | The name of the excel file.                 |
+------------------------+---------------------------------------------+
| Sheet Name             | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Start Column           | The first column of the data range.         |
+------------------------+---------------------------------------------+
| End Column             | The last column of the data range.          |
+------------------------+---------------------------------------------+

Write Excel
^^^^^^^^^^^

   |image70|

   Function: To write a data array into an excel sheet

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel FIlename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Starting Cell          | The first cell to start writing the data.   |
+------------------------+---------------------------------------------+
| Data Array             | The data array that will be used to write   |
|                        | into the excel.                             |
+------------------------+---------------------------------------------+

Excel
~~~~~

   A group of functions that will perform excel actions without having
   excel opened on the screen. All action will be done in the backend.

Add Column
^^^^^^^^^^

   |image71|

   Function: This function is to add columns in the excel file. It will
   use the insert column function of excel.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel Filename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Column Start           | The starting column to add new columns.     |
+------------------------+---------------------------------------------+
| Count                  | The number of columns to be added.          |
+------------------------+---------------------------------------------+

Add New Sheet
^^^^^^^^^^^^^

   |image72|

   Function: This function is to add a new sheet to an excel file.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel Filename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the new sheet to be added.      |
+------------------------+---------------------------------------------+

Add Row
^^^^^^^

   |image73|

   Function: This function is to add rows in the excel file. It will use
   the insert row function of excel.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel Filename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Row Start              | The starting row to add new rows.           |
+------------------------+---------------------------------------------+
| Count                  | The number of rows to be added.             |
+------------------------+---------------------------------------------+

Cell Format
^^^^^^^^^^^

   |image74|

   Function: This function is to set the format for a range of cells in
   an excel file.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel FIlename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Cell Start             | The first cell of the cell range.           |
+------------------------+---------------------------------------------+
| Cell End               | THe last cell of the cell range.            |
+------------------------+---------------------------------------------+
| Cell Format            | The format to be set for the cell range.    |
+------------------------+---------------------------------------------+

Clear Sheet
^^^^^^^^^^^

   |image75|

   Function: This function is to clear the cell in an excel sheet.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel Filename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Cell Start             | The first cell of the cell range.           |
+------------------------+---------------------------------------------+
| Cell End               | The last cell of the cell range.            |
+------------------------+---------------------------------------------+

Color Cell
^^^^^^^^^^

   |image76|

   Function: This function is to color the cell in an excel file.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel Filename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Cell Start             | The first cell of the cell range.           |
+------------------------+---------------------------------------------+
| Cell End               | The last cell of the cell range.            |
+------------------------+---------------------------------------------+
| Color                  | The color to be set for the cell range.     |
+------------------------+---------------------------------------------+

Delete Column
^^^^^^^^^^^^^

   |image77|

   Function: This function is to delete columns in the excel file.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel Filename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Column Start           | The first column to be deleted.             |
+------------------------+---------------------------------------------+
| Count                  | The number of columns to be deleted.        |
+------------------------+---------------------------------------------+

Delete Row
^^^^^^^^^^

   |image78|

   Function: This function is to delete rows in the excel file.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel Filename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Row Start              | The first row to be deleted.                |
+------------------------+---------------------------------------------+
| Count                  | The number of rows to be deleted.           |
+------------------------+---------------------------------------------+

Delete Sheet
^^^^^^^^^^^^

   |image79|

   Function: This function is to delete a sheet of an excel file.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel Filename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+

Import Data by Column
^^^^^^^^^^^^^^^^^^^^^

   |image80|

   Function: Import entire column from one excel sheet to another

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Source Excel Filename  | The file path of the source excel file.     |
+------------------------+---------------------------------------------+
| Sheetname              | THe name of the source excel sheet.         |
+------------------------+---------------------------------------------+
| Column                 | The column to be copied.                    |
+------------------------+---------------------------------------------+
| Headers                | An option to import the headers or not.     |
+------------------------+---------------------------------------------+
| Target Excel Filename  | The file path of the target excel file.     |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the target excel sheet.         |
+------------------------+---------------------------------------------+
| Column                 | The column to import the data.              |
+------------------------+---------------------------------------------+

Insert Formula
^^^^^^^^^^^^^^

   |image81|

   Function: To insert formula to a row of cells

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel Filename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Starting Column        | The column of the first cell.               |
+------------------------+---------------------------------------------+
| Starting Row           | The row of the first cell.                  |
+------------------------+---------------------------------------------+
| Rows                   | The number of rows after the first cell.    |
+------------------------+---------------------------------------------+
| Formula                | The formula to be inserted into the cell    |
|                        | range.                                      |
+------------------------+---------------------------------------------+

Merge Cell
^^^^^^^^^^

   |image82|

   Function: To merge two or more cells together

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel FIlename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Cell Start             | The first cell of the cell range.           |
+------------------------+---------------------------------------------+
| Cell End               | The last cell of the cell range.            |
+------------------------+---------------------------------------------+
| Text                   | Th text to be written into the merged cell. |
+------------------------+---------------------------------------------+
| Alignment              | The text alignment of the merged cell.      |
+------------------------+---------------------------------------------+
| Bold                   | An option to make the text bold.            |
+------------------------+---------------------------------------------+
| Italic                 | An option to make the text italic.          |
+------------------------+---------------------------------------------+

Remove Duplicates
^^^^^^^^^^^^^^^^^

   |image83|

   Function: To remove all duplicates in the same column

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel Filename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Column                 | THe column to remove duplicates.            |
+------------------------+---------------------------------------------+
| Headers                | An option for if there is a header or not.  |
+------------------------+---------------------------------------------+

Rename Sheet
^^^^^^^^^^^^

   |image84|

   Function: To rename an existing sheet

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel FIlename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| New Sheetname          | The new name of the excel sheet.            |
+------------------------+---------------------------------------------+

Write To Cell
^^^^^^^^^^^^^

   |image85|

   Function: To write data to a cell

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel FIlename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Cell                   | The cell to write the data.                 |
+------------------------+---------------------------------------------+
| Value                  | The value to be written to the cell.        |
+------------------------+---------------------------------------------+
| Type                   | The type of the value.                      |
+------------------------+---------------------------------------------+

File/Saving
~~~~~~~~~~~

   A group of functions that will perform file operation such as copying
   or moving files and renaming files.

Copy Move File
^^^^^^^^^^^^^^

   |image86|

   Function: To copy or move a file

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Source File            | The file path of the source file.           |
+------------------------+---------------------------------------------+
| Target File            | The file path of the target file.           |
+------------------------+---------------------------------------------+
| Operation              | An option to copy or move the source file.  |
+------------------------+---------------------------------------------+
| Replace                | An option to replace the existing file in   |
|                        | the destination path.                       |
+------------------------+---------------------------------------------+

Delete File
^^^^^^^^^^^

   |image87|

   Function: To delete an existing file.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| File Path              | The file path of the file to be deleted.    |
+------------------------+---------------------------------------------+

Move Rename File
^^^^^^^^^^^^^^^^

   |image88|

   Function: To rename or move the file.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Source                 | The file path of the source file.           |
+------------------------+---------------------------------------------+
| Destination            | The file path of the destination.           |
+------------------------+---------------------------------------------+

Read File
^^^^^^^^^

   |image89|

   Function: To read a file and store it in a variable

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Variable               | The variable to store the data.             |
+------------------------+---------------------------------------------+
| Path                   | The file path of the file to be read.       |
+------------------------+---------------------------------------------+

Read File To
^^^^^^^^^^^^

   |image90|

   Function: To read a file and store it in a variable

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Filename               | The file path of the file to be read.       |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the data.             |
+------------------------+---------------------------------------------+

Rename File
^^^^^^^^^^^

   |image91|

   Function: To rename a file

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Source File            | The file path of the source file.           |
+------------------------+---------------------------------------------+
| Target Filename        | The new file name.                          |
+------------------------+---------------------------------------------+
| Replace                | An option to replace if another file with   |
|                        | the same name exists.                       |
+------------------------+---------------------------------------------+

Write File
^^^^^^^^^^

   |image92|

   Function: To write data to a file

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Path                   | The file path of the file.                  |
+------------------------+---------------------------------------------+
| Content                | The data to be written to the file.         |
+------------------------+---------------------------------------------+

Write To File
^^^^^^^^^^^^^

   |image93|

   Function: To write data to a file

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Filename               | The file path of the file.                  |
+------------------------+---------------------------------------------+
| Content                | The data to be written to the file.         |
+------------------------+---------------------------------------------+
| Option                 | An option to append or replace the data     |
|                        | inside the file.                            |
+------------------------+---------------------------------------------+

Helper Function
~~~~~~~~~~~~~~~

   A group of functions that will allow the user to further enhance
   their workflow by using scripting language such as JavaScript and
   Python.

Close Window
^^^^^^^^^^^^

   |image94|

   Function: To close the currently opened window

Copy Text
^^^^^^^^^

   |image95|

   Function: To copy text to the clipboard

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Text                   | The text to be copied.                      |
+------------------------+---------------------------------------------+

Paste Text
^^^^^^^^^^

   |image96|

   Function: To paste the text in the clipboard

Run CMD
^^^^^^^

   |image97|

   Function: To run a command prompt command

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Command                | The cmd command to be run.                  |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the output.           |
+------------------------+---------------------------------------------+

Run JS
^^^^^^

   |image98|

   Function: To run a JavaScript code

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Script                 | The JavaScript code to be run.              |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the output.           |
+------------------------+---------------------------------------------+

Run Python
^^^^^^^^^^

   |image99|

   Function: To run a Python code

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Script                 | The Python code to be run.                  |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the output.           |
+------------------------+---------------------------------------------+

Run R
^^^^^

   |image100|

   Function: To run a R code

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Script                 | The R code to be run.                       |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the output.           |
+------------------------+---------------------------------------------+

Run Sikuli
^^^^^^^^^^

   |image101|

   Function: To run a Sikuli code

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Script                 | The Sikuli code to be run.                  |
+------------------------+---------------------------------------------+

Set Clipboard
^^^^^^^^^^^^^

   |image102|

   Function: To set a value to the clipboard

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Input                  | The value to be set to clipboard            |
+------------------------+---------------------------------------------+

Miscellaneous
~~~~~~~~~~~~~

API Basic
^^^^^^^^^

   |image103|

   Function: Call a web API and save the raw response.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| URL                    | URL of the API.                             |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the output.           |
+------------------------+---------------------------------------------+

Custom Script
^^^^^^^^^^^^^

   |image104|

   Function: To make some custom script to run in the flow.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Script                 | The custom script to be run.                |
+------------------------+---------------------------------------------+

For Loop
^^^^^^^^

   |image105|

   Function: Used to repeat a specific action multiple times.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Data Array             | The data array to determine the loop count. |
+------------------------+---------------------------------------------+
| Delimiter              | The delimiter that is used in the data      |
|                        | array.                                      |
+------------------------+---------------------------------------------+

Loop
^^^^

   |image106|

   Function: To create a loop in the workflow

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Collection             | The number of loops.                        |
+------------------------+---------------------------------------------+
| Iterator               | The iterator for the loop.                  |
+------------------------+---------------------------------------------+
| Counter                | The counter to be used in the loop.         |
+------------------------+---------------------------------------------+

OCR – Read from Image
^^^^^^^^^^^^^^^^^^^^^

   |image107|

   Function: This action allows text extraction with the use of OCR.
   (Hand-written words would not be read by OCR)

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Image Filename         | The file path of the image.                 |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the output.           |
+------------------------+---------------------------------------------+

OCR – Read Screen by Region
^^^^^^^^^^^^^^^^^^^^^^^^^^^

   |image108|

   Function: This action allows the user to read the screen content of a
   region

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Start Position         | The first coordinate on the screen.         |
+------------------------+---------------------------------------------+
| End Position           | The second coordinate on the screen.        |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the output.           |
+------------------------+---------------------------------------------+

Outlook – Compose Email
^^^^^^^^^^^^^^^^^^^^^^^

   |image109|

   Function: To send an email using the outlook application

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Subject                | The subject of the email.                   |
+------------------------+---------------------------------------------+
| To                     | The receiver of the email.                  |
+------------------------+---------------------------------------------+
| CC                     | The receiver of a CC of the email.          |
+------------------------+---------------------------------------------+
| Message                | The body of the email.                      |
+------------------------+---------------------------------------------+
| Attachment             | An option to choose if there is an          |
|                        | attachment for the email.                   |
+------------------------+---------------------------------------------+
| Attachment File        | The file path of the attachment file.       |
+------------------------+---------------------------------------------+

Read Text File
^^^^^^^^^^^^^^

   |image110|

   Function: This action is able to read a text file and store it with a
   variable.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Filepath               | The file path of the file.                  |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the output.           |
+------------------------+---------------------------------------------+

Set Value
^^^^^^^^^

   |image111|

   Function: This action is able to set a value and store it into a
   variable for next use.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Variable Name          | The variable to store the value.            |
+------------------------+---------------------------------------------+
| Input                  | The value of the variable.                  |
+------------------------+---------------------------------------------+

Snap
^^^^

   |image112|

   Function: This action is able to snap a whole screen as a picture.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| File Name              | The name of the file.                       |
+------------------------+---------------------------------------------+

Split Text
^^^^^^^^^^

   |image113|

   Function: This function can split the text with any character.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Text to split          | The text to be split                        |
+------------------------+---------------------------------------------+
| Split By               | The character to be used to split the tet   |
+------------------------+---------------------------------------------+
| Result Array           | The array to store the result               |
+------------------------+---------------------------------------------+

Substring
^^^^^^^^^

   |image114|

   Function: This function is to get the substring from a line of text.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Variable Name to Sub   | The line of text.                           |
| String                 |                                             |
+------------------------+---------------------------------------------+
| Store Sub String       | The variable to store the substring.        |
| Variable Name          |                                             |
+------------------------+---------------------------------------------+
| Start Index            | The starting index of the substring.        |
+------------------------+---------------------------------------------+
| Length                 | The length of the substring.                |
+------------------------+---------------------------------------------+

Tesseract OCR
^^^^^^^^^^^^^

   |image115|

   Function: To use Tesseract OCR

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Filename (Image)       | The file path of the image.                 |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the output.           |
+------------------------+---------------------------------------------+

Timestamp
^^^^^^^^^

   |image116|

   Function: This action is able to generate date and time.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Format                 | The format of the timestamp.                |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the output.           |
+------------------------+---------------------------------------------+

Vault – Get Secret
^^^^^^^^^^^^^^^^^^

   |image117|

   Function: This action is able to protect the confidential data such
   as username and password from getting by others.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Username               | The username of Central account.            |
+------------------------+---------------------------------------------+
| Password               | The password of Central account.            |
+------------------------+---------------------------------------------+
| Envelope               | The envelope that store the secret.         |
+------------------------+---------------------------------------------+
| Key                    | The key to access the envelope.             |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the output.           |
+------------------------+---------------------------------------------+

Wait
^^^^

   |image118|

   Function: To wait before going to the next action

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Time in seconds        | The seconds to wait.                        |
+------------------------+---------------------------------------------+

WhatsApp DD
^^^^^^^^^^^

   |image119|

   Function: To use the WhatsApp API

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| URL                    | The URL of the WhatsApp API.                |
+------------------------+---------------------------------------------+
| Recipient              | The recipient of the message.               |
+------------------------+---------------------------------------------+
| Message                | The message to be sent.                     |
+------------------------+---------------------------------------------+

PDF
~~~

   A group of functions that will perform actions related to PDF such as
   convert files to PDF or read PDF to text.

Print PDF - Excel
^^^^^^^^^^^^^^^^^

   |image120|

   Function: To print a cell range of an excel to PDF

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Excel FIlename         | The file path of the excel file.            |
+------------------------+---------------------------------------------+
| Sheetname              | The name of the excel sheet.                |
+------------------------+---------------------------------------------+
| Cell Range             | The range of cells to be printed to PDF.    |
+------------------------+---------------------------------------------+
| PDF Filepath           | The file path of the generated PDF file.    |
+------------------------+---------------------------------------------+

Print PDF - Word
^^^^^^^^^^^^^^^^

   |image121|

   Function: To print a word doc to PDF

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Word Filepath          | The file path of the Word file.             |
+------------------------+---------------------------------------------+
| PDF Filepath           | The file path of the generated PDF file.    |
+------------------------+---------------------------------------------+

Read PDF
^^^^^^^^

   |image122|

   Function: Read the PDF

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Filepath               | The file path of the PDF file.              |
+------------------------+---------------------------------------------+
| Out                    | The variable to store the data.             |
+------------------------+---------------------------------------------+

Run Options
~~~~~~~~~~~

Showing Outputs
~~~~~~~~~~~~~~~

   A group of functions that will output text to the output log.

Echo
^^^^

   |image123|

   Function: Echo text or variable that was set at previous action.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Text                   | The variable which stores the data that     |
|                        | need to be output to the log.               |
+------------------------+---------------------------------------------+

Echo Text
^^^^^^^^^

   |image124|

   Function: Echo the text

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Text                   | The string of text that need to be output   |
|                        | to the log.                                 |
+------------------------+---------------------------------------------+

Using Variable
~~~~~~~~~~~~~~

Word
~~~~

   A group of functions that will perform word actions such as creating
   a new word document or typing text into a word document.

Create Word Doc
^^^^^^^^^^^^^^^

   |image125|

   Function: Create a Word file for you.

Insert Text
^^^^^^^^^^^

   |image126|

   Function: Insert text to Word file

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Text                   | The string of text to be insert into the    |
|                        | opened Word file                            |
+------------------------+---------------------------------------------+

Open Word
^^^^^^^^^

   |image127|

   Function: Open the Word file.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| File Path              | The file path of the Word file.             |
+------------------------+---------------------------------------------+

Read Text from Word
^^^^^^^^^^^^^^^^^^^

   |image128|

   Function: Read text inside the Word file.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Filepath               | File path of the Word file.                 |
+------------------------+---------------------------------------------+

Replace String
^^^^^^^^^^^^^^

   |image129|

   Function: Replace string inside the word.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Find What              | The string of text to be replaced.          |
+------------------------+---------------------------------------------+
| Replace With           | The string of text to replace with.         |
+------------------------+---------------------------------------------+

Save Document
^^^^^^^^^^^^^

   |image130|

   Function: Save the document.

Save & Close
^^^^^^^^^^^^

   |image131|

   Function: Save the document and close it.

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| File Path              | File path of the Word file.                 |
+------------------------+---------------------------------------------+
| Overwrite              | An option to overwrite any existing file    |
|                        | with the same name.                         |
+------------------------+---------------------------------------------+

Conditions
~~~~~~~~~~

IFELSE
^^^^^^

   |image132|

   Function: If not then else

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Condition              | The condition for the if-else.              |
+------------------------+---------------------------------------------+

Database
~~~~~~~~

Select From Database
^^^^^^^^^^^^^^^^^^^^

   |image133|

   Function: Select from database table

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Database Type          | Type of the database.                       |
+------------------------+---------------------------------------------+
| Server                 | Server name.                                |
+------------------------+---------------------------------------------+
| Database               | Database name.                              |
+------------------------+---------------------------------------------+
| Username               | Database login username.                    |
+------------------------+---------------------------------------------+
| Password               | Database login password.                    |
+------------------------+---------------------------------------------+
| Select Query           | Query to select from database table.        |
+------------------------+---------------------------------------------+
| Output Variable        | Output to display select query.             |
+------------------------+---------------------------------------------+

Terminal
~~~~~~~~

Capture Screen
^^^^^^^^^^^^^^

   |image134|

   Function:

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Path                   |                                             |
+------------------------+---------------------------------------------+

Connect
^^^^^^^

   |image135|

   Function:

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| HostName               |                                             |
+------------------------+---------------------------------------------+
| HostPort               |                                             |
+------------------------+---------------------------------------------+
| ModelName              |                                             |
+------------------------+---------------------------------------------+
| VerifyCert             |                                             |
+------------------------+---------------------------------------------+
| EnableTLS              |                                             |
+------------------------+---------------------------------------------+
| CodePage               |                                             |
+------------------------+---------------------------------------------+
| Path                   |                                             |
+------------------------+---------------------------------------------+

Disconnect
^^^^^^^^^^

   |image136|

   Function:

Login
^^^^^

   |image137|

   Function:

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| UserName               |                                             |
+------------------------+---------------------------------------------+
| Password               |                                             |
+------------------------+---------------------------------------------+

Send Key
^^^^^^^^

   |image138|

   Function:

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Key                    |                                             |
+------------------------+---------------------------------------------+

Send Text
^^^^^^^^^

   |image139|

   Function:

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| InputText              |                                             |
+------------------------+---------------------------------------------+

Terminal PUB400
^^^^^^^^^^^^^^^

   |image140|

   Function:

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Username               |                                             |
+------------------------+---------------------------------------------+
| Password               |                                             |
+------------------------+---------------------------------------------+
| Library                |                                             |
+------------------------+---------------------------------------------+
| Filename               |                                             |
+------------------------+---------------------------------------------+
| OutputFIlename         |                                             |
+------------------------+---------------------------------------------+

Collections
~~~~~~~~~~~

Create List
^^^^^^^^^^^

   |image141|

   Function: To create a list of data

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| List Name              | The name of the list                        |
+------------------------+---------------------------------------------+
| Data                   | The data to store in the list               |
+------------------------+---------------------------------------------+

Loop From To
^^^^^^^^^^^^

   |image142|

   Function: To create a loop

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| From                   |                                             |
+------------------------+---------------------------------------------+
| To                     |                                             |
+------------------------+---------------------------------------------+
| Iterator               |                                             |
+------------------------+---------------------------------------------+

Loop Sub – Click on Element
^^^^^^^^^^^^^^^^^^^^^^^^^^^

   |image143|

   Function: Click on XPATH

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| Click Type             | Left click, right click or double click.    |
+------------------------+---------------------------------------------+
| XPATH                  | XPATH to click.                             |
+------------------------+---------------------------------------------+

Loop Sub – Type on Element
^^^^^^^^^^^^^^^^^^^^^^^^^^

   |image144|

   Function: Type array to web element

+------------------------+---------------------------------------------+
| Parameter              | Description                                 |
+------------------------+---------------------------------------------+
| XPATH                  | XPATH of the input bar.                     |
+------------------------+---------------------------------------------+
| Text                   | Text to type on XPATH.                      |
+------------------------+---------------------------------------------+

Execute
-------

1. To run the workflow, click the “run” button next to the “save”
   button.

|image145|

2. A pop-up will appear.

|image146|

3. Tick the “Require Web Browser” option if browser is used in the
   workflow

|image147|

4. Click on the “Start” button and the workflow will start.

|image148|

Export
------

To export the workflow, click the “export” button and it will be
exported to a .ddp file. The exported file can be found at the
“Downloads” folder.

|image149|

Icons
-----

.. |image28| image:: media/image28.png
   :width: 1.13954in
   :height: 1.09359in
.. |image29| image:: media/image29.png
   :width: 3.3685in
   :height: 2.36763in
.. |image30| image:: media/image30.png
   :width: 5.14795in
   :height: 2.73481in
.. |image31| image:: media/image31.png
   :width: 4.86521in
   :height: 2.59793in
.. |image32| image:: media/image32.png
   :width: 4.89694in
   :height: 2.60321in
.. |image33| image:: media/image33.png
   :width: 4.72441in
   :height: 2.55906in
.. |image34| image:: media/image34.png
   :width: 4.72441in
   :height: 2.55906in
.. |image35| image:: media/image35.png
   :width: 4.72441in
   :height: 2.55906in
.. |image36| image:: media/image36.png
   :width: 4.72441in
   :height: 2.55906in
.. |image37| image:: media/image37.png
   :width: 4.72441in
   :height: 2.55906in
.. |image38| image:: media/image38.png
   :width: 4.72441in
   :height: 2.55906in
.. |image39| image:: media/image39.png
   :width: 4.72441in
   :height: 2.55906in
.. |image40| image:: media/image40.png
   :width: 4.72441in
   :height: 2.55906in
.. |image41| image:: media/image41.png
   :width: 4.72441in
   :height: 2.55906in
.. |image42| image:: media/image42.png
   :width: 4.72441in
   :height: 2.55906in
.. |image43| image:: media/image43.png
   :width: 4.72441in
   :height: 2.55906in
.. |image44| image:: media/image44.png
   :width: 4.72441in
   :height: 2.55906in
.. |image45| image:: media/image45.png
   :width: 4.72441in
   :height: 2.55906in
.. |image46| image:: media/image46.png
   :width: 4.72441in
   :height: 2.55906in
.. |image47| image:: media/image47.png
   :width: 4.72441in
   :height: 2.55906in
.. |image48| image:: media/image48.png
   :width: 4.72441in
   :height: 2.55906in
.. |image49| image:: media/image49.png
   :width: 4.72441in
   :height: 2.55906in
.. |image50| image:: media/image50.png
   :width: 4.72441in
   :height: 2.55906in
.. |image51| image:: media/image51.png
   :width: 4.72441in
   :height: 2.55906in
.. |image52| image:: media/image52.png
   :width: 4.72441in
   :height: 2.55906in
.. |image53| image:: media/image53.png
   :width: 4.72441in
   :height: 2.55906in
.. |image54| image:: media/image54.png
   :width: 4.72441in
   :height: 2.55906in
.. |image55| image:: media/image55.png
   :width: 4.72441in
   :height: 2.55906in
.. |image56| image:: media/image56.png
   :width: 4.72441in
   :height: 2.55906in
.. |image57| image:: media/image57.png
   :width: 4.72441in
   :height: 2.55906in
.. |image58| image:: media/image58.png
   :width: 4.72441in
   :height: 2.55906in
.. |image59| image:: media/image59.png
   :width: 4.72441in
   :height: 2.55906in
.. |image60| image:: media/image60.png
   :width: 4.72441in
   :height: 2.55906in
.. |image61| image:: media/image61.png
   :width: 4.72441in
   :height: 2.55906in
.. |image62| image:: media/image62.png
   :width: 4.72441in
   :height: 2.55906in
.. |image63| image:: media/image63.png
   :width: 4.72441in
   :height: 2.55906in
.. |image64| image:: media/image64.png
   :width: 4.72441in
   :height: 2.55906in
.. |image65| image:: media/image65.png
   :width: 4.72441in
   :height: 2.55906in
.. |image66| image:: media/image66.png
   :width: 4.72441in
   :height: 2.55906in
.. |image67| image:: media/image67.png
   :width: 4.72441in
   :height: 2.55906in
.. |image68| image:: media/image68.png
   :width: 4.72441in
   :height: 2.55906in
.. |image69| image:: media/image69.png
   :width: 4.72441in
   :height: 2.55906in
.. |image70| image:: media/image70.png
   :width: 4.72441in
   :height: 2.55906in
.. |image71| image:: media/image71.png
   :width: 4.72441in
   :height: 2.55906in
.. |image72| image:: media/image72.png
   :width: 4.72441in
   :height: 2.55906in
.. |image73| image:: media/image73.png
   :width: 4.72441in
   :height: 2.55906in
.. |image74| image:: media/image74.png
   :width: 4.72441in
   :height: 2.55906in
.. |image75| image:: media/image75.png
   :width: 4.72441in
   :height: 2.55906in
.. |image76| image:: media/image76.png
   :width: 4.72441in
   :height: 2.55906in
.. |image77| image:: media/image77.png
   :width: 4.72441in
   :height: 2.55906in
.. |image78| image:: media/image78.png
   :width: 4.72441in
   :height: 2.55906in
.. |image79| image:: media/image79.png
   :width: 4.72441in
   :height: 2.55906in
.. |image80| image:: media/image80.png
   :width: 4.72441in
   :height: 2.55906in
.. |image81| image:: media/image81.png
   :width: 4.72441in
   :height: 2.55906in
.. |image82| image:: media/image82.png
   :width: 4.72441in
   :height: 2.55906in
.. |image83| image:: media/image83.png
   :width: 4.72441in
   :height: 2.55906in
.. |image84| image:: media/image84.png
   :width: 4.72441in
   :height: 2.55906in
.. |image85| image:: media/image85.png
   :width: 4.72441in
   :height: 2.55906in
.. |image86| image:: media/image86.png
   :width: 4.72441in
   :height: 2.55906in
.. |image87| image:: media/image87.png
   :width: 4.72441in
   :height: 2.55906in
.. |image88| image:: media/image88.png
   :width: 4.72441in
   :height: 2.55906in
.. |image89| image:: media/image89.png
   :width: 4.72441in
   :height: 2.55906in
.. |image90| image:: media/image90.png
   :width: 4.72441in
   :height: 2.55906in
.. |image91| image:: media/image91.png
   :width: 4.72441in
   :height: 2.55906in
.. |image92| image:: media/image92.png
   :width: 4.72441in
   :height: 2.55906in
.. |image93| image:: media/image93.png
   :width: 4.72441in
   :height: 2.55906in
.. |image94| image:: media/image94.png
   :width: 4.72441in
   :height: 2.55906in
.. |image95| image:: media/image95.png
   :width: 4.72441in
   :height: 2.55906in
.. |image96| image:: media/image96.png
   :width: 4.72441in
   :height: 2.55906in
.. |image97| image:: media/image97.png
   :width: 4.72441in
   :height: 2.55906in
.. |image98| image:: media/image98.png
   :width: 4.72441in
   :height: 2.55906in
.. |image99| image:: media/image99.png
   :width: 4.72441in
   :height: 2.55906in
.. |image100| image:: media/image100.png
   :width: 4.72441in
   :height: 2.55906in
.. |image101| image:: media/image101.png
   :width: 4.72441in
   :height: 2.55906in
.. |image102| image:: media/image102.png
   :width: 4.72441in
   :height: 2.55906in
.. |image103| image:: media/image103.png
   :width: 4.72441in
   :height: 2.55906in
.. |image104| image:: media/image104.png
   :width: 4.72441in
   :height: 2.55906in
.. |image105| image:: media/image105.png
   :width: 4.72441in
   :height: 2.55906in
.. |image106| image:: media/image106.png
   :width: 4.72441in
   :height: 2.55906in
.. |image107| image:: media/image107.png
   :width: 4.72441in
   :height: 2.55906in
.. |image108| image:: media/image108.png
   :width: 4.72441in
   :height: 2.55906in
.. |image109| image:: media/image109.png
   :width: 4.72441in
   :height: 2.55906in
.. |image110| image:: media/image110.png
   :width: 4.72441in
   :height: 2.55906in
.. |image111| image:: media/image111.png
   :width: 4.72441in
   :height: 2.55906in
.. |image112| image:: media/image112.png
   :width: 4.72441in
   :height: 2.55906in
.. |image113| image:: media/image113.png
   :width: 4.72441in
   :height: 2.55906in
.. |image114| image:: media/image114.png
   :width: 4.72441in
   :height: 2.55906in
.. |image115| image:: media/image115.png
   :width: 4.72441in
   :height: 2.55906in
.. |image116| image:: media/image116.png
   :width: 4.72441in
   :height: 2.55906in
.. |image117| image:: media/image117.png
   :width: 4.72441in
   :height: 2.55906in
.. |image118| image:: media/image118.png
   :width: 4.72441in
   :height: 2.55906in
.. |image119| image:: media/image119.png
   :width: 4.72441in
   :height: 2.55906in
.. |image120| image:: media/image120.png
   :width: 4.72441in
   :height: 2.55906in
.. |image121| image:: media/image121.png
   :width: 4.72441in
   :height: 2.55906in
.. |image122| image:: media/image122.png
   :width: 4.72441in
   :height: 2.55906in
.. |image123| image:: media/image123.png
   :width: 4.72441in
   :height: 2.55906in
.. |image124| image:: media/image124.png
   :width: 4.72441in
   :height: 2.55906in
.. |image125| image:: media/image125.png
   :width: 4.72441in
   :height: 2.55906in
.. |image126| image:: media/image126.png
   :width: 4.72441in
   :height: 2.55906in
.. |image127| image:: media/image127.png
   :width: 4.72441in
   :height: 2.55906in
.. |image128| image:: media/image128.png
   :width: 4.72441in
   :height: 2.55906in
.. |image129| image:: media/image129.png
   :width: 4.72441in
   :height: 2.55906in
.. |image130| image:: media/image130.png
   :width: 4.72441in
   :height: 2.55906in
.. |image131| image:: media/image131.png
   :width: 4.72441in
   :height: 2.55906in
.. |image132| image:: media/image132.png
   :width: 4.72441in
   :height: 2.55906in
.. |image133| image:: media/image133.png
   :width: 4.72441in
   :height: 2.55906in
.. |image134| image:: media/image134.png
   :width: 4.72441in
   :height: 2.55906in
.. |image135| image:: media/image135.png
   :width: 4.72441in
   :height: 2.55906in
.. |image136| image:: media/image136.png
   :width: 4.72441in
   :height: 2.55906in
.. |image137| image:: media/image137.png
   :width: 4.72441in
   :height: 2.55906in
.. |image138| image:: media/image138.png
   :width: 4.72441in
   :height: 2.55906in
.. |image139| image:: media/image139.png
   :width: 4.72441in
   :height: 2.55906in
.. |image140| image:: media/image140.png
   :width: 4.72441in
   :height: 2.55906in
.. |image141| image:: media/image141.png
   :width: 4.72441in
   :height: 2.55906in
.. |image142| image:: media/image142.png
   :width: 4.72441in
   :height: 2.55906in
.. |image143| image:: media/image143.png
   :width: 4.72441in
   :height: 2.55906in
.. |image144| image:: media/image144.png
   :width: 4.72441in
   :height: 2.55906in
.. |image145| image:: media/image21.png
   :width: 3.21967in
   :height: 0.77677in
.. |image146| image:: media/image22.png
   :width: 4.30144in
   :height: 1.60839in
.. |image147| image:: media/image23.png
   :width: 4.31455in
   :height: 1.61616in
.. |image148| image:: media/image24.png
   :width: 4.308in
   :height: 1.61371in
.. |image149| image:: media/image145.png
   :width: 2.91667in
   :height: 0.72708in