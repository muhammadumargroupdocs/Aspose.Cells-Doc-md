---
title: Add WordArt Watermark to Worksheet in Aspose.Cells
type: docs
weight: 20
url: /net/add-wordart-watermark-to-worksheet-in-aspose-cells/
---

{{% alert color="primary" %}} 

Use WordArt to add special text effects to spreadsheets. For example, stretch a title across the top of the file, decorate text, and make text fit a preset shape, or apply text to an Excel sheet as a background watermark. The WordArt becomes an object that you can move or position in spreadsheets to add decoration.

{{% /alert %}} 

The following example shows how to add a WordArt shape to set a background watermark for a worksheet.

After running the code the output file contains a pale red WordArt watermark.

**The output file** 

![todo:image_alt_text](/download/thumbnails/5020417/157748250)

**C#**

{{< highlight csharp >}}

 string FilePath = @"..\..\..\Sample Files\";

string FileName = FilePath + "Add WordArt Watermark to Worksheet.xlsx";

//Instantiate a new Workbook

Workbook workbook = new Workbook();

//Get the first default sheet

Worksheet sheet = workbook.Worksheets[0];

//Add Watermark

Aspose.Cells.Drawing.Shape wordart = sheet.Shapes.AddTextEffect(MsoPresetTextEffect.TextEffect1,

"CONFIDENTIAL", "Arial Black", 50, false, true

, 18, 8, 1, 1, 130, 800);

//Get the fill format of the word art

MsoFillFormat wordArtFormat = wordart.FillFormat;

//Set the color

wordArtFormat.ForeColor = System.Drawing.Color.Red;

//Set the transparency

wordArtFormat.Transparency = 0.9;

//Make the line invisible

MsoLineFormat lineFormat = wordart.LineFormat;

lineFormat.IsVisible = false;

//Save the file

workbook.Save(FileName);

{{< /highlight >}}
### **Download Sample Code**
- [Codeplex](https://asposeopenxml.codeplex.com/SourceControl/latest#Aspose.Cells Features missing in OpenXML/Add WordArt Watermark/)
- [Github](https://github.com/aspose-cells/Aspose.Cells-for-.NET/tree/master/Plugins/Aspose.Cells%20Vs%20OpenXML%20Spreadsheets/OpenXML%20Missing%20Features/Add%20WordArt%20Watermark)
- [Code.MSDN](https://code.msdn.microsoft.com/AsposeCells-Features-8fba7c3c/view/SourceCode#content)
### **Download Running Example**
- [Codeplex](https://asposecellsopenxml.codeplex.com/releases/view/619160)
- [Github](https://github.com/aspose-cells/Aspose.Cells-for-.NET/releases/tag/MissingFeaturesOpenXMLExcelv1.1)
- [Code.MSDN](https://code.msdn.microsoft.com/AsposeCells-Features-8fba7c3c)