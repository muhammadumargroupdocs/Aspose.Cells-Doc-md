---
title: Determine if Paper Size of Worksheet is Automatic
type: docs
weight: 90
url: /net/determine-if-paper-size-of-worksheet-is-automatic/
---

## **Possible Usage Scenarios**
Most of the time, the paper size of the worksheet is automatic. When it is automatic, it is often set as *Letter*. Sometimes the user sets the paper size of the worksheet as per their requirements. In this case, the paper size is not automatic. You can find if the worksheet paper size is automatic or not using the [Worksheet.PageSetup.IsAutomaticPaperSize](https://apireference.aspose.com/net/cells/aspose.cells/pagesetup/properties/isautomaticpapersize) property.
## **Determine if Paper Size of Worksheet is Automatic**
The sample code given below loads the following two Excel files

- [samplePageSetupIsAutomaticPaperSize-False.xlsx](attachments/48136585/48496681.xlsx)
- [samplePageSetupIsAutomaticPaperSize-True.xlsx](attachments/48136585/48496682.xlsx)

and find if the paper size of their first worksheet is automatic or not. In Microsoft Excel, you can check if the paper size is automatic or not via the Page Setup window as shown in this screenshot.

![todo:image_alt_text](determine-if-paper-size-of-worksheet-is-automatic_1.png)
## **Sample Code**
{{< gist "aspose-com-gists" "24a8eac23c3325e20dababecf735a43b" "Examples-CSharp-Worksheets-PageSetupFeatures-DetermineIfPaperSizeOfWorksheetIsAutomatic.cs" >}}
## **Console Output**
Here is the console output of the above sample code when executed with the given sample Excel files.

{{< highlight java >}}

 First Worksheet of First Workbook - IsAutomaticPaperSize: False

First Worksheet of Second Workbook - IsAutomaticPaperSize: True

{{< /highlight >}}