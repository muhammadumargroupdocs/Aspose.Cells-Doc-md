---
title: Removing Slicer
type: docs
weight: 30
url: /java/removing-slicer/
---

## **Possible Usage Scenarios**
If you want to remove slicer in Microsoft Excel, just select it and press the *Delete* button. Similarly, if you want to remove it using Aspose.Cells API programmatically, please use the [Worksheet.getSlicers().remove()](https://apireference.aspose.com/cells/java/com.aspose.cells/slicercollection#remove\(com.aspose.cells.Slicer\)) method. It will remove the slicer from the worksheet. 
## **Removing Slicer**
The following sample code loads the [sample Excel file](attachments/66948424/67338504.xlsx) that contains an existing slicer. It accesses the slicers and then removes it. Finally, it saves the workbook as [output Excel file](attachments/66948424/67338502.xlsx). The following screenshot shows the slicer that will be removed after the execution of the sample code.

![todo:image_alt_text](removing-slicer_1.png)
## **Sample Code**
{{< gist "aspose-com-gists" "439a68a5e4305388c50ca306ef238de5" "Slicers-RemovingSlicer.java" >}}