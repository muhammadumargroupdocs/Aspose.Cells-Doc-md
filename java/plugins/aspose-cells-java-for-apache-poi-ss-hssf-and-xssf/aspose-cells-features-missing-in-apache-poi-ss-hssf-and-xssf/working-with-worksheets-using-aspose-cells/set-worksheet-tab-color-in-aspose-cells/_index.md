---
title: Set Worksheet Tab Color in Aspose.Cells
type: docs
weight: 90
url: /java/set-worksheet-tab-color-in-aspose-cells/
---

## **Aspose.Cells - Set Worksheet Tab Color**
Aspose.Cells allows you to change the color of individual worksheet tabs to make them prominent from the rest. For example, you can make Expenses red, Sales green, Assets blue, etc.
#### **Setting Worksheet Tab Color with Microsoft Excel**
1. Right-click a tab in the tab-sheet at the bottom of the current worksheet.
1. Select **Tab color**.
1. Select a color from the palette.
1. Click **OK**.

**Java**

{{< highlight java >}}

 //Instantiate a new Workbook

Workbook workbook = new Workbook(dataPath + "workbook.xls");

//Get the first worksheet in the book

Worksheet worksheet = workbook.getWorksheets().get(0);

//Set the tab color

worksheet.setTabColor(Color.getRed());

//Save the Excel file

workbook.save(dataPath + "AsposeColoredTab_Out.xls");

{{< /highlight >}}
## **Download Running Code**
- [CodePlex](https://asposecellsjavaapachepoi.codeplex.com/releases/view/618615)
- [GitHub](https://github.com/aspose-cells/Aspose.Cells-for-Java/releases/tag/Aspose.Cells_Java_for_Apache_POI_SS-v1.0.0)
## **Download Sample Code**
- [CodePlex](https://asposecellsjavaapachepoi.codeplex.com/SourceControl/latest#src/main/java/com/aspose/cells/examples/asposefeatures/worksheets/SetWorksheetTabColor.java)
- [GitHub](https://github.com/aspose-cells/Aspose.Cells-for-Java/tree/master/Plugins/Aspose_Cells_for_Apache_POI/src/main/java/com/aspose/cells/examples/asposefeatures/worksheets/SetWorksheetTabColor.java)

{{% alert color="primary" %}} 

For more details, visit [Set Worksheet Tab Color](http://docs.aspose.com:8082/docs/display/cellsjava/Set+Worksheet+Tab+Color).

{{% /alert %}}
