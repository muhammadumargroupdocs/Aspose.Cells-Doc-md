---
title: Verify Password Used to Protect the Worksheet
type: docs
weight: 290
url: /java/verify-password-used-to-protect-the-worksheet/
---

{{% alert color="primary" %}} 

Aspose.Cells APIs have enhanced the [Protection](https://apireference.aspose.com/java/cells/com.aspose.cells/Protection) class by introducing some useful properties & methods. One such method is the [verifyPassword](https://apireference.aspose.com/java/cells/com.aspose.cells/protection#verifyPassword\(java.lang.String\)) which allows specifying a password as an instance of String and verifies if the same password has been used to protect the Worksheet.

{{% /alert %}} 
### **Verify Password Used to Protect the Worksheet**
The [Protection.verifyPassword](https://apireference.aspose.com/java/cells/com.aspose.cells/protection#verifyPassword\(java.lang.String\)) method returns **true** if the specified password matches with the password used to protect the given worksheet, **false** if the specified password does not match. Following piece of code uses the [Protection.verifyPassword](https://apireference.aspose.com/java/cells/com.aspose.cells/protection#verifyPassword\(java.lang.String\)) method in conjunction with [Protection.isProtectedWithPassword](https://apireference.aspose.com/java/cells/com.aspose.cells/protection#IsProtectedWithPassword) property to detect the password protection, and verifies the password.

{{< gist "aspose-com-gists" "a20e8fa273e7cfa37d032b8211fcf8bf" "Examples-src-main-java-com-aspose-cells-examples-articles-VerifyPasswordtoProtectWorksheet-VerifyPasswordtoProtectWorksheet.java" >}}
