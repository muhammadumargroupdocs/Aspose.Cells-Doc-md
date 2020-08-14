---
title: Copy Row Heights of Source Range to Destination Range
type: docs
weight: 250
url: /java/copy-row-heights-of-source-range-to-destination-range/
---

{{% alert color="primary" %}} 

Sometime user needs to copy row heights of source range to destination range. Aspose.Cells provides [PasteType.ROW_HEIGHTS](https://apireference.aspose.com/java/cells/com.aspose.cells/pastetype#ROW_HEIGHTS) enum for this purpose. When you will set [PasteOptions.setPasteType()](https://apireference.aspose.com/java/cells/com.aspose.cells/pasteoptions#PasteType) property with [PasteType.ROW_HEIGHTS](https://apireference.aspose.com/java/cells/com.aspose.cells/pastetype#ROW_HEIGHTS) enum then heights of all rows inside the source range will be copied to the destination range.

{{% /alert %}} 
#### **Copy Row Heights of Source Range to Destination Range**
The following sample code explains how to use [PasteType.ROW_HEIGHTS](https://apireference.aspose.com/java/cells/com.aspose.cells/pastetype#ROW_HEIGHTS) enum to copy row heights of source range into destination range. Once you will open the output excel file generated by this code in Microsoft Excel, you will see that destination range row heights are exactly the same as source range row heights.

{{< gist "aspose-com-gists" "a20e8fa273e7cfa37d032b8211fcf8bf" "Examples-src-main-java-com-aspose-cells-examples-articles-CopyRowHeights-CopyRowHeights.java" >}}