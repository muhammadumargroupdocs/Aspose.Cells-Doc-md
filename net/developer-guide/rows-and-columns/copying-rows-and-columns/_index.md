---
title: Copying Rows and Columns
type: docs
weight: 40
url: /net/copying-rows-and-columns/
---

## **Introduction**

Sometimes, you need to copy rows and columns in a worksheet without copying the entire worksheet. With Aspose.Cells, it is possible to copy rows and columns within or between workbooks.
When a row (or column) is copied, the data contained in it, including formulas - with updated references - and values, comments, formatting, hidden cells, images, and other drawing objects are copied too.

## **Copying Rows and Columns with Microsoft Excel**

1. Select the row or column that you want to copy.
1. To copy rows or columns, click **Copy** on the **Standard** toolbar, or press **CTRL**+**C**.
1. Select a row or column below or to the right of where you want to copy your selection.
1. When you are copying rows or columns, click **Copied Cells** on the **Insert** menu.

{{% alert color="primary" %}}

If you click **Paste** on the **Standard** toolbar or press **CTRL**+**V** instead of clicking a command on the **Insert** menu, any contents of the destination cells are replaced.

{{% /alert %}}

## **Pasting Rows and Columns using Paste Options with Microsoft Excel**

1. Select the cells that contain the data or other attributes that you want to copy.
1. On the Home tab, click **Copy**.
1. Click the first cell in the area where you want to **paste** what you copied.
1. On the Home tab, click the arrow next to **Paste**, and then select **Paste** Special.
1. Select the **options** you want.

## **Using Aspose.Cells**

### **Copying Rows**

Aspose.Cells provides the [**CopyRow**](https://apireference.aspose.com/cells/net/aspose.cells/cells/methods/copyrow) method of the [**Cells**](https://apireference.aspose.com/cells/net/aspose.cells/cells) class. This method copies all types of data including formulas, values, comments, cell formats, hidden cells, images and other drawing objects from the source row to the destination row.

The [**CopyRow**](https://apireference.aspose.com/cells/net/aspose.cells/cells/methods/copyrow) method takes the following parameters:

- the source [**Cells**](https://apireference.aspose.com/cells/net/aspose.cells/cells) object,
- the source row index, and
- the destination row index.

Use this method to copy a row within a sheet, or to another sheet. The [**CopyRow**](https://apireference.aspose.com/cells/net/aspose.cells/cells/methods/copyrow) method works in a similar way to Microsoft Excel. So, for example, you don't need to set the height of the destination row explicitly, that value is copied too.

The following example shows how to copy a row in a worksheet. It uses a template Microsoft Excel file and copies the second row (complete with data, formatting, comments, images and so on) and paste it to the 12th row in the same worksheet.

You can skip the step that gets the source row height using the [**Cells.GetRowHeight**](https://apireference.aspose.com/cells/net/aspose.cells/cells/methods/getrowheight) method and then sets the destination row height using the [**Cells.SetRowHeight**](https://apireference.aspose.com/cells/net/aspose.cells/cells/methods/setrowheight) method as the [**CopyRow**](https://apireference.aspose.com/cells/net/aspose.cells/cells/methods/copyrow) method automatically takes care of the row height.

{{< gist "aspose-com-gists" "24a8eac23c3325e20dababecf735a43b" "Examples-CSharp-RowsColumns-Copying-CopyingRows-1.cs" >}}

{{% alert color="primary" %}}

When copying rows, it is important to note related images, charts or other drawing objects as this is the same with Microsoft Excel:

1. If the source row index is 5, the image, chart, etc., is copied if it is contained in the three rows (the starting row index is 4 and the ending row index is 6).
1. The existing images, charts, etc. in the destination row will not be removed.

{{% /alert %}}

### **Copying Columns**

Aspose.Cells provides the [**CopyColumn**](hhttps://apireference.aspose.com/cells/net/aspose.cells/cells/methods/copycolumn) method of the [**Cells**](https://apireference.aspose.com/cells/net/aspose.cells/cells) class, this method copies all types of data, including formulas - with updated references - and values, comments, cell formats, hidden cells, images and other drawing objects from the source column to the destination column.

The [**CopyColumn**](hhttps://apireference.aspose.com/cells/net/aspose.cells/cells/methods/copycolumn) method takes the following parameters:

- the source [**Cells**](https://apireference.aspose.com/cells/net/aspose.cells/cells) object,
- source column index, and
- the destination column index.

Use the [**CopyColumn**](hhttps://apireference.aspose.com/cells/net/aspose.cells/cells/methods/copycolumn) method to copy a column within a sheet or to another sheet.

This example copies a column from a worksheet and pastes it into a worksheet in another workbook.

{{< gist "aspose-com-gists" "24a8eac23c3325e20dababecf735a43b" "Examples-CSharp-RowsColumns-Copying-CopyingColumns-1.cs" >}}

### **Pasting Rows/Columns with Paste Options**

Aspose.Cells now provides [**PasteOptions**](https://apireference.aspose.com/cells/net/aspose.cells/pasteoptions) while using functions [**CopyRows**](https://apireference.aspose.com/cells/net/aspose.cells.cells/copyrows/methods/2) and [**CopyColumns**](https://apireference.aspose.com/cells/net/aspose.cells.cells/copycolumns/methods/1). It allows to set appropriate paste option similar to Excel.

{{< gist "aspose-com-gists" "24a8eac23c3325e20dababecf735a43b" "Examples-CSharp-RowsColumns-Copying-PastingRowsColumnsWithPasteOptions-1.cs" >}}
