---
title: Generate Conditional Formatting DataBars Images
type: docs
weight: 40
url: /net/generate-conditional-formatting-databars-images/
---

{{% alert color="primary" %}} 

Sometimes, you need to generate images of Conditional Formatting DataBars. You can use Aspose.Cells [DataBar.ToImage()](https://apireference.aspose.com/net/cells/aspose.cells/databar/methods/toimage) method to generate these images. This article shows how to generate a DataBar image using Aspose.Cells.

{{% /alert %}} 

The following sample code generates the DataBar image of cell C1. First, it accesses the format condition object of the cell, and then from that object, it accesses the [DataBar](https://apireference.aspose.com/net/cells/aspose.cells/databar) object and uses its [ToImage()](https://apireference.aspose.com/net/cells/aspose.cells/databar/methods/toimage) method to generate the image of the cell. Finally, it saves the image on disk.



{{< gist "aspose-com-gists" "922f990b02cf4e04a328bd6f37029af8" "Examples-CSharp-Articles-ManageConditionalFormatting-GenerateDatabarImage-1.cs" >}}
