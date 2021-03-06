---
title: Disable Exporting Frame Scripts and Document Properties
type: docs
weight: 410
url: /java/disable-exporting-frame-scripts-and-document-properties/
---

{{% alert color="primary" %}} 

Aspose.Cells exports frame scripts and document properties while converting a workbook into HTML. The 8.6.0 version of Aspose.Cells for Java introduces an option that allows you optionally disable exporting frame scripts and document properties. Please use the [HtmlSaveOptions.setExportFrameScriptsAndProperties()](https://apireference.aspose.com/java/cells/com.aspose.cells/htmlsaveoptions#ExportFrameScriptsAndProperties) property to disable the export.

{{% /alert %}} 
#### **Disable exporting frame scripts and document properties**
The following sample code allows you to disable exporting frame scripts and document properties. Once you convert a workbook into HTML, the output file will not contain any frame scripts and document properties.

Here is a sample code.

{{< gist "aspose-com-gists" "a20e8fa273e7cfa37d032b8211fcf8bf" "Examples-src-main-java-com-aspose-cells-examples-articles-DisableExporting-DisableExporting.java" >}}
