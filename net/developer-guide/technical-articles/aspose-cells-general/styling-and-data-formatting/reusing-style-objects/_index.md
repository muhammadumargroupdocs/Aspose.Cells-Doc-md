---
title: Reusing Style Objects
type: docs
weight: 30
url: /net/reusing-style-objects/
---

{{% alert color="primary" %}}

Reusing style objects can save memory and make a program faster.

{{% /alert %}}

To apply some formatting to a large range of cells in a worksheet:

1. Create a style object.
1. Specify the attributes.
1. Apply the style to the cells in the range.

{{< gist "aspose-com-gists" "24a8eac23c3325e20dababecf735a43b" "Examples-CSharp-Articles-StylingAndDataFormatting-ReusingStyleObjects-ReusingStyleObjects.cs" >}}

{{% alert color="primary" %}}

Because the [**Cell.GetStyle**](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/getstyle)/[**Cell.SetStyle**](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/setstyle) approach uses a lot less memory, and is efficient, the older Cell.Style property which consumed a lot of unnecessary memory, was removed with the release of Aspose.Cells 7.1.0.

{{% /alert %}}
