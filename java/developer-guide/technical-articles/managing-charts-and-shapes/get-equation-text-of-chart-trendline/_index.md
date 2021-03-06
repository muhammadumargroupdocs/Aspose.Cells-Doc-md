---
title: Get Equation Text of Chart Trendline
type: docs
weight: 90
url: /java/get-equation-text-of-chart-trendline/
---

{{% alert color="primary" %}} 

You can retrieve the Equation Text of Chart Trendline using Aspose.Cells. Aspose.Cells provides [Trendline.getDataLabels().getText()](https://apireference.aspose.com/java/cells/com.aspose.cells/datalabels#Text) property which returns the Equation Text of chart trendline. To make use of this property, you will first have to call [Chart.calculate()](https://apireference.aspose.com/java/cells/com.aspose.cells/chart#calculate\(\)) method.

{{% /alert %}} 
#### **Example**
The following screenshot shows the Chart with a Trendline and its Equation Text is shown in Red color. We will retrieve this text using the [Trendline.getDataLabels().getText()](https://apireference.aspose.com/java/cells/com.aspose.cells/datalabels#Text) property in the following sample code.

![todo:image_alt_text](get-equation-text-of-chart-trendline_1.png)
#### **Sample Code**
{{< gist "aspose-com-gists" "a20e8fa273e7cfa37d032b8211fcf8bf" "Examples-src-main-java-com-aspose-cells-examples-articles-GetEquationText-GetEquationText.java" >}}
#### **Output**
This is the console output of the above sample code.

{{< highlight java >}}

 Equation Text: y = 8.1333x + 5

{{< /highlight >}}
