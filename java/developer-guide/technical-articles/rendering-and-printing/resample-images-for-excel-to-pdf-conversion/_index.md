---
title: Resample Images for Excel to PDF Conversion
type: docs
weight: 250
url: /java/resample-images-for-excel-to-pdf-conversion/
---

{{% alert color="primary" %}} 

While working with big Microsoft Excel files with lots of images, you might need to compress images that have been added to reduce the output PDF file size and improve the overall conversion performance. Aspose.Cells supports re-sampling added images to reduce the output PDF file size and improve performance.

{{% /alert %}} 
#### **Resample Images for Excel to PDF Conversion**
Please see the following sample code that describes how to perform the task using the Aspose.Cells API. The example converts a Microsoft Excel file to a PDF file while compressing the images in the file.

{{< gist "aspose-com-gists" "a20e8fa273e7cfa37d032b8211fcf8bf" "Examples-src-main-java-com-aspose-cells-examples-articles-ResampleImagesforExceltoPDFConversion-ResampleImagesforExceltoPDFConversion.java" >}}

{{% alert color="primary" %}} 

Using the [PdfSaveOptions.setImageResample](https://apireference.aspose.com/java/cells/com.aspose.cells/pdfsaveoptions#setImageResample\(int,%20int\)) option minimizes the size of the output PDF but it may affect the image quality a bit.

{{% /alert %}} {{% alert color="primary" %}} 

If your spreadsheet contains formulas, it is best to call [Workbook.calculateFormula()](https://apireference.aspose.com/java/cells/com.aspose.cells/workbook#calculateFormula\(\)) just before rendering the spreadsheet to PDF format. Doing so will ensure that the formula dependent values are recalculated, and the correct values are rendered in the PDF.

{{% /alert %}}