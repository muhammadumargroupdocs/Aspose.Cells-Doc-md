---
title: Accessing Table from Cell and Adding Values inside it using Row and Column Offsets
type: docs
weight: 230
url: /net/accessing-table-from-cell-and-adding-values-inside-it-using-row-and-column-offsets/
---

{{% alert color="primary" %}} 

Normally, you add values inside the Table or List Object using [Cell.PutValue()](https://apireference.aspose.com/net/cells/aspose.cells/cell/methods/putvalue/index) method. But sometimes, you might need to add values inside the Table or List Object using the row and column offsets.

In order to access Table or List Object from a cell, use the [Cell.GetTable()](https://apireference.aspose.com/net/cells/aspose.cells/cell/methods/gettable) method. To add values inside it using the row and column offsets, use the [ListObject.PutCellValue](https://apireference.aspose.com/net/cells/aspose.cells.tables/listobject/methods/putcellvalue) method.

{{% /alert %}} 

The following screenshot shows the source Excel file used inside the code. It contains the empty table and highlights the cell D5 which lies inside the table. We will access this table from cell D5 using [Cell.GetTable()](https://apireference.aspose.com/net/cells/aspose.cells/cell/methods/gettable) method and then add the values inside it using both [Cell.PutValue()](https://apireference.aspose.com/net/cells/aspose.cells/cell/methods/putvalue/index) and [ListObject.PutCellValue](https://apireference.aspose.com/net/cells/aspose.cells.tables/listobject/methods/putcellvalue) methods.

|![todo:image_alt_text](accessing-table-from-cell-and-adding-values-inside-it-using-row-and-column-offsets_1.png)|
| :- |
The following screenshot shows the output Excel file generated by the code. As you can see cell D5 has a value and cell F6 which is at the offset 2,2 of the table has a value.

|![todo:image_alt_text](accessing-table-from-cell-and-adding-values-inside-it-using-row-and-column-offsets_2.png)|
| :- |
## **Sample Code**
The following sample code loads the source Excel file as shown in the above screenshot and adds values inside the table and generates the output Excel file as shown above.



{{< gist "aspose-com-gists" "24a8eac23c3325e20dababecf735a43b" "Examples-CSharp-Articles-ManagingRowsColumnsCells-AccessTableFromCellAndAddValue-AccessTableFromCellAndAddValue.cs" >}}
