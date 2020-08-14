---
title: Convert CSV to JSON
type: docs
weight: 220
url: /net/convert-csv-to-json/
---

## **Convert CSV to JSON**
Aspose.Cells supports converting CSV to JSON. For this, the API provides [ExportRangeToJsonOptions](https://apireference.aspose.com/net/cells/aspose.cells.utility/exportrangetojsonoptions) and [JsonUtility](https://apireference.aspose.com/net/cells/aspose.cells.utility/jsonutility) classes. The [ExportRangeToJsonOptions](https://apireference.aspose.com/net/cells/aspose.cells.utility/exportrangetojsonoptions) class provides the options for exporting range to JSON. The [ExportRangeToJsonOptions](https://apireference.aspose.com/net/cells/aspose.cells.utility/exportrangetojsonoptions) class has the following properties.

- [ExportAsString](https://apireference.aspose.com/net/cells/aspose.cells.utility/exportrangetojsonoptions/properties/exportasstring): This exports the string value of the cells to JSON.
- [HasHeaderRow](https://apireference.aspose.com/net/cells/aspose.cells.utility/exportrangetojsonoptions/properties/hasheaderrow): This indicates whether the range contains a header row.
- [Indent](https://apireference.aspose.com/net/cells/aspose.cells.utility/exportrangetojsonoptions/properties/indent): Indicates the indent.

The [JsonUtility](https://apireference.aspose.com/net/cells/aspose.cells.utility/jsonutility) class exports the JSON using the export options set with the [ExportRangeToJsonOptions](https://apireference.aspose.com/net/cells/aspose.cells.utility/exportrangetojsonoptions) class.

The following code sample demonstrates the use of [ExportRangeToJsonOptions](https://apireference.aspose.com/net/cells/aspose.cells.utility/exportrangetojsonoptions) and [JsonUtility](https://apireference.aspose.com/net/cells/aspose.cells.utility/jsonutility) classes to load the [source CSV file](attachments/104267887/104398879.csv) and prints the [J](attachments/104267887/104398871.csv)SON output in the console.
### **Sample Code**
{{< gist "aspose-com-gists" "922f990b02cf4e04a328bd6f37029af8" "Examples-CSharp-LoadingSavingConvertingAndManaging-ConvertCsvToJson-1.cs" >}}
### **Console Output**
[
{
"id": 1,
"language": "Java",
"edition": "third",
"author": "Herbert Schildt",
"streetAddress": 126,
"city": "San Jone",
"state": "CA",
"postalCode": 394221
},
{
"id": 2,
"language": "C++",
"edition": "second",
"author": "EAAAA",
"streetAddress": 126,
"city": "San Jone",
"state": "CA",
"postalCode": 394221
},
{
"id": 3,
"language": ".Net",
"edition": "second",
"author": "E.Balagurusamy",
"streetAddress": 126,
"city": "San Jone",
"state": "CA",
"postalCode": 394221
}
]