---
title: Check Version Number of the Component
type: docs
weight: 70
url: /java/check-version-number-of-the-component/
---

{{% alert color="primary" %}} 

In some cases, you might wonder what version of the product you have. Often we build new fixes (bug fixes for the user scenarios which they point out) and post them in the forums against their need urgently. A version number may consist of two to four parts/components: major, minor, build, and revision. The major and minor components are required; the build and revision components are optional, but the build component is required if the revision component is defined. All defined components must be integers greater than or equal to 0. The format of the version number is as follows. Optional components are shown in square brackets ('[' and ']'):

major.minor[.build[.revision]] , we may increase a part by 1 and make a new version. Normally, we increase the last part by 1 and build a new fix to post it into the forums for the users.

This document describes some ways to check which version of the component is installed on your system.

{{% /alert %}} 
#### **Checking the version number**
##### **1) Manual Way**
If you have Java version/fix (Aspose.Cells for Java), you can unzip the Aspose.Cells library jar file, open the MANIFEST file with notepad and search the string i.e.., "Specification-Version: " to check its value.

![todo:image_alt_text](check-version-number-of-the-component_1.png)


**Figure:** Checking the version number of the Java fix
##### **2) Using the APIs**
You may also use the following APIs to get the version number of the product.



{{< gist "aspose-com-gists" "439a68a5e4305388c50ca306ef238de5" "Examples-src-main-java-com-aspose-cells-examples-introduction-CheckVersionNumberOfComponent-CheckVersionNumberOfComponent.java" >}}
