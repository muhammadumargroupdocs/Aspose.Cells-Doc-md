---
title: Disable Exporting Frame Scripts and Document Properties
type: docs
weight: 310
url: /net/disable-exporting-frame-scripts-and-document-properties/
---

{{% alert color="primary" %}} 

Aspose.Cells exports frame scripts and document properties while converting a workbook into HTML. The 8.6.0 version of Aspose.Cells for .NET introduces an option which allows you optionally disable exporting frame scripts and doctment properties. Please use the HtmlSaveOptions.ExportFrameScriptsAndProperties property to disable the export.

{{% /alert %}} 
## **Disable exporting frame scripts and document properties**
The following sample code allows you to disable exporting frame scripts and document properties. Once you convert a workbook into HTML, the output file will not contain any frame scripts and document properties.



{{< gist "aspose-cells" "c326c6c668fc372e30569fa9e0f6bf4b" "Examples-CSharp-Articles-HtmlExportFrameScripts-1.cs" >}}