---
title: Propagate Formula in Table or List Object automatically while entering data in new rows
type: docs
weight: 980
url: /java/propagate-formula-in-table-or-list-object-automatically-while-entering-data-in-new-rows/
---

## **Possible Usage Scenarios**
Sometimes, you want a formula in your Table or List Object automatically propagates to new rows while entering new data. This is the default behavior of Microsoft Excel. In order to achieve the same thing with Aspose.Cells, please use [ListColumn.Formula](https://apireference.aspose.com/java/cells/com.aspose.cells/listcolumn#Formula) property.
## **Propagate Formula in Table or List Object automatically while entering data in new rows**
The following sample code creates a Table or List Object in such a way that the formula in column B will automatically propagate to new rows when you will enter new data. Please check the [output excel file](5472519.xlsx) generated with this code. If you enter any number in cell A3, you will see, the formula in cell B2 automatically propagates to cell B3.
## **Sample Code**
{{< gist "aspose-com-gists" "a20e8fa273e7cfa37d032b8211fcf8bf" "Examples-src-main-java-com-aspose-cells-examples-articles-PropagateFormulaInTableorListObject-PropagateFormulaInTableorListObject.java" >}}
