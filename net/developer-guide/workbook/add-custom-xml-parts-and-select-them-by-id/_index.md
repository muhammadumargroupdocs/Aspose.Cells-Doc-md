---
title: Add Custom XML Parts and Select them by ID
type: docs
weight: 10
url: /net/add-custom-xml-parts-and-select-them-by-id/
---

## **Possible Usage Scenarios**

Custom XML Parts are the XML data that is stored inside the Microsoft Excel documents and are used by the applications that deal with them. There is no direct way of adding them using Microsoft Excel UI at the moment. However, you can add them programmatically in various ways e.g. using VSTO, using Aspose.Cells etc. Please use [**Workbook.CustomXmlParts.Add()**](https://apireference.aspose.com/cells/net/aspose.cells.markup/customxmlpartcollection/methods/add) method if you want to add Custom XML Part using Aspose.Cells API. You can also set its ID, using the [**CustomXmlPart.ID**](https://apireference.aspose.com/cells/net/aspose.cells.markup/customxmlpart/properties/id) property. Similarly, if you want to select Custom XML Part by ID, you can use [**Workbook.CustomXmlParts.SelectByID()**](https://apireference.aspose.com/cells/net/aspose.cells.markup/customxmlpartcollection/methods/selectbyid) method.

## **Add Custom XML Parts and Select them by ID**

The following sample code first adds four Custom XML Parts using [**Workbook.CustomXmlParts.Add()**](https://apireference.aspose.com/cells/net/aspose.cells.markup/customxmlpartcollection/methods/add) method. It then sets their IDs using [**CustomXmlPart.ID**](h**ttps://apireference.aspose.com/net/cells/aspose.cells.markup/customxmlpart/properties/id**) property. Finally, it finds or selects one of the added Custom XML Part using [**Workbook.CustomXmlParts.SelectByID()**](https://apireference.aspose.com/cells/net/aspose.cells.markup/customxmlpartcollection/methods/selectbyid) method. Please also see the console output of the code given below for reference.

## **Sample Code**

{{< gist "aspose-com-gists" "24a8eac23c3325e20dababecf735a43b" "Workbook-AddCustomXMLPartsAndSelectThemByID.cs" >}}

## **Console Output**

{{< highlight java >}}

 Found: CustomXmlPart ID Sport

{{< /highlight >}}
