---
title: Implement Errors and Boolean Value in Russian or Any Other Language
type: docs
weight: 40
url: /net/implement-errors-and-boolean-value-in-russian-or-any-other-language/
---

## **Possible Usage Scenarios**
If you are using Microsoft Excel in Russian Locale or Language or any other Locale or Language, it will display Errors and Boolean values according to that Locale or Language. You can achieve a similar behavior using Aspose.Cells by using the [Workbook.Settings.GlobalizationSettings](https://apireference.aspose.com/net/cells/aspose.cells/workbooksettings/properties/globalizationsettings) property. You will have to override the following methods of [GlobalizationSettings](https://apireference.aspose.com/net/cells/aspose.cells/globalizationsettings) class.

- [GlobalizationSettings.GetErrorValueString()](https://apireference.aspose.com/net/cells/aspose.cells/globalizationsettings/methods/geterrorvaluestring)
- [GlobalizationSettings.GetBooleanValueString()](https://apireference.aspose.com/net/cells/aspose.cells/globalizationsettings/methods/getbooleanvaluestring)
## **Implement Errors and Boolean Value in Russian or Any Other Language**
The following sample code illustrates how to implement Errors and Boolean Value in Russian or Any Other Language. Please check the [Sample Excel File](attachments/48136575/73990159.xlsx) used in this code and its [Output PDF](attachments/48136575/73990160.pdf). The screenshot shows the difference between Sample Excel File and the Output PDF for a reference.

![todo:image_alt_text](implement-errors-and-boolean-value-in-russian-or-any-other-language_1.png)
## **Sample Code**
{{< gist "aspose-com-gists" "24a8eac23c3325e20dababecf735a43b" "Examples-CSharp-WorkbookSettings-ImplementErrorsAndBooleanValueInRussianOrAnyOtherLanguage.cs" >}}