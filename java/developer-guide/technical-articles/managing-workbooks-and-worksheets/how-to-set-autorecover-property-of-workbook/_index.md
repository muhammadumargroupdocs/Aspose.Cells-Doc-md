---
title: How to set AutoRecover property of Workbook
type: docs
weight: 160
url: /java/how-to-set-autorecover-property-of-workbook/
---

{{% alert color="primary" %}} 

You can use Aspose.Cells to set AutoRecover property of workbook. The default value of this property is **true**. When you set it **false** on a workbook, Microsoft Excel disables Autorecover (Autosave) on that Excel file.

Aspose.Cells provides [Workbook.getSettings().setAutoRecover()](https://apireference.aspose.com/java/cells/com.aspose.cells/workbooksettings#AutoRecover) property to enable or disable this option.

{{% /alert %}} 
#### **Example**
The following code explains how to use [Workbook.getSettings().setAutoRecover()](https://apireference.aspose.com/java/cells/com.aspose.cells/workbooksettings#AutoRecover) property of the workbook. The code first reads the default value of this property which is **true**, then it sets it as **false** and saves the workbook. Then it reads the workbook again and reads the value of this property which is false at this time.

{{< gist "aspose-com-gists" "a20e8fa273e7cfa37d032b8211fcf8bf" "Examples-src-main-java-com-aspose-cells-examples-articles-SetAutoRecoverProperty-SetAutoRecoverProperty.java" >}}
#### **Output**
Here is the console output of the above sample code.

{{< highlight java >}}

 AutoRecover: true

AutoRecover: false

{{< /highlight >}}