---
title: Show and Hide Gridlines and Row Column Headers
type: docs
weight: 30
url: /net/show-and-hide-gridlines-and-row-column-headers/
---

{{% alert color="primary" %}} 

Aspose.Cells supports hiding and showing Gridlines of the worksheet which are visible by default. It also provides controlling visibility of Row Column Headers of the worksheet.

{{% /alert %}} 
## **Show and Hide Gridlines**
All Excel worksheets have gridlines by default. They help delineate cells so that it is easy to enter data into particular cells. Gridlines enable us to view a worksheet as a collection of cells, where each cell is easily identifiable.
### **Controlling the Visibility of the Gridlines**
Aspose.Cells provides a class, [Workbook](https://apireference.aspose.com/net/cells/aspose.cells/workbook), that represents a Microsoft Excel file. The [Workbook](https://apireference.aspose.com/net/cells/aspose.cells/workbook) class contains a [Worksheets](https://apireference.aspose.com/net/cells/aspose.cells/workbook/properties/worksheets) collection that allows developers to access each worksheet in the Excel file. A worksheet is represented by the [Worksheet](https://apireference.aspose.com/net/cells/aspose.cells/worksheet) class. The [Worksheet](https://apireference.aspose.com/net/cells/aspose.cells/worksheet) class provides a wide range of properties and methods for managing a worksheet. To control the visibility of gridlines, use the [Worksheet](https://apireference.aspose.com/net/cells/aspose.cells/worksheet) class [IsGridlinesVisible](https://apireference.aspose.com/net/cells/aspose.cells/worksheet/properties/isgridlinesvisible) property. [IsGridlinesVisible](https://apireference.aspose.com/net/cells/aspose.cells/worksheet/properties/isgridlinesvisible) is a Boolean property, which means that it can only store a **true** or **false** value.
#### **Making Gridlines Visible**
Make the gridlines visible by setting the [Worksheet](https://apireference.aspose.com/net/cells/aspose.cells/worksheet) class [IsGridlinesVisible](https://apireference.aspose.com/net/cells/aspose.cells/worksheet/properties/isgridlinesvisible) property to **true**.
#### **Hiding Gridlines**
Hide gridlines by setting the [Worksheet](https://apireference.aspose.com/net/cells/aspose.cells/worksheet) class [IsGridlinesVisible](https://apireference.aspose.com/net/cells/aspose.cells/worksheet/properties/isgridlinesvisible) property to **false**.

A complete example is given below that demonstrates the use of the [IsGridlinesVisible](https://apireference.aspose.com/net/cells/aspose.cells/worksheet/properties/isgridlinesvisible) property by opening an excel file(book1.xls), hiding the gridlines on the first worksheet and saving the modified file as output.xls.



{{< gist "aspose-com-gists" "24a8eac23c3325e20dababecf735a43b" "Examples-CSharp-Worksheets-Display-DisplayHideGridlines-1.cs" >}}
## **Show and Hide Row Column Headers**
All worksheets in an Excel file are composed of cells that are arranged in rows and columns. All rows and columns have unique values that are used to identify them and to identify individual cells. For example, rows are numbered – 1, 2, 3, 4, etc. – and columns are ordered alphabetically – A, B, C, D, etc. The row and column values are displayed in the headers. Using Aspose.Cells, developers can control the visibility of these row and column headers.
### **Controlling the Visibility of the Worksheets**
Aspose.Cells provides a class, [Workbook](https://apireference.aspose.com/net/cells/aspose.cells/workbook), that represents a Microsoft Excel file. The [Workbook](https://apireference.aspose.com/net/cells/aspose.cells/workbook) class contains a [Worksheets](https://apireference.aspose.com/net/cells/aspose.cells/workbook/properties/worksheets) collection that allows developers to access each worksheet in the Excel file. A worksheet is represented by the [Worksheet](https://apireference.aspose.com/net/cells/aspose.cells/worksheet) class. The [Worksheet](https://apireference.aspose.com/net/cells/aspose.cells/worksheet) class provides a wide range of properties and methods for managing a worksheet. To control the visibility of row and column headers, use the [Worksheet](https://apireference.aspose.com/net/cells/aspose.cells/worksheet) class [IsRowColumnHeadersVisible](https://apireference.aspose.com/net/cells/aspose.cells/worksheet/properties/isrowcolumnheadersvisible) property. [IsRowColumnHeadersVisible](https://apireference.aspose.com/net/cells/aspose.cells/worksheet/properties/isrowcolumnheadersvisible) is a Boolean property, which means that it can only store a **true** or **false** value.
#### **Making Row/Column Headers Visible**
Make row and column headers visible by setting the [Worksheet](https://apireference.aspose.com/net/cells/aspose.cells/worksheet) class [IsRowColumnHeadersVisible](https://apireference.aspose.com/net/cells/aspose.cells/worksheet/properties/isrowcolumnheadersvisible) property to **true**.
#### **Hiding Row/Column Headers**
Hide row and column headers by setting the [Worksheet](https://apireference.aspose.com/net/cells/aspose.cells/worksheet) class [IsRowColumnHeadersVisible](https://apireference.aspose.com/net/cells/aspose.cells/worksheet/properties/isrowcolumnheadersvisible) property to **false**.

A complete example is given below that shows how to use the [IsRowColumnHeadersVisible](https://apireference.aspose.com/net/cells/aspose.cells/worksheet/properties/isrowcolumnheadersvisible) property by opening an excel file(book1.xls), hiding the row and column headers on the first worksheet and saving the modified file as output.xls.



{{< gist "aspose-com-gists" "24a8eac23c3325e20dababecf735a43b" "Examples-CSharp-Worksheets-Display-DisplayHideRowColumnHeaders-1.cs" >}}

{{% alert color="primary" %}} 

It is also possible to use the [UnhideRows](https://apireference.aspose.com/net/cells/aspose.cells/cells/methods/unhiderows) and [UnhideColumns](https://apireference.aspose.com/net/cells/aspose.cells/cells/methods/unhidecolumns) methods of the [Cells ](https://apireference.aspose.com/net/cells/aspose.cells/cells)class to make multiple rows and columns visible.

{{% /alert %}}