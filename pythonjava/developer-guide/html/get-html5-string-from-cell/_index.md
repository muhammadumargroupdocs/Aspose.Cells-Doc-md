---
title: Get HTML5 string from Cell
type: docs
weight: 40
url: /pythonjava/get-html5-string-from-cell/
---

## **Get HTML5 string from Cell**
Using Aspose.Cells for Python via Java, you can get the HTML string form the cell. This can be achieved by using the [getHtmlString(boolean html5)](https://apireference.aspose.com/cells/python/asposecells.api/cell#getHtmlString\(boolean\)) method provided by the API. If you pass **false** as a parameter, it will return you Normal HTML but if you pass **true** as a parameter, it will return HTML5 string.

The following sample code creates a workbook object and adds some text in cell A1 of the first worksheet. It then gets the Normal HTML and HTML5 string from cell A1 using the [getHtmlString(boolean html5)](https://apireference.aspose.com/cells/python/asposecells.api/cell#getHtmlString\(boolean\)) method and prints them.
## **Sample Code**
{{< gist "aspose-com-gists" "f3cac13617c487b51b47cc9ae1d7c008" "HTML-GetHTML5StringFromCell.py" >}}

The following is the output generated by the above-provided code snippet.
## **Output**
{{< highlight java >}}

 Normal:

<Font Style="FONT-FAMILY: Arial;FONT-SIZE: 10pt;COLOR: #000000;">This is some text.</Font>

Html5:

<div Style="FONT-FAMILY: Arial;FONT-SIZE: 10pt;COLOR: #000000;">This is some text.</div>

{{< /highlight >}}