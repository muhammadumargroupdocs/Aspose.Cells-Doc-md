---
title: Track Conversion Progress of Excel to TIFF
type: docs
weight: 140
url: /java/track-conversion-progress-of-excel-to-tiff/
---

## **Possible Usage Scenarios**

Sometimes converting large excel files can take some time. During this time, you might want to show the document conversion progress instead of just a loading screen to enhance the usability of your application. Aspose.Cells supports tracking document conversion process by providing the **[IPageSavingCallback](https://apireference.aspose.com/cells/java/com.aspose.cells/IPageSavingCallback)** interface. The **[IPageSavingCallback](https://apireference.aspose.com/cells/java/com.aspose.cells/IPageSavingCallback)** interface provides **[PageStartSaving](https://apireference.aspose.com/cells/java/com.aspose.cells/ipagesavingcallback#pageStartSaving(com.aspose.cells.PageStartSavingArgs))** and **[PageEndSaving](https://apireference.aspose.com/cells/java/com.aspose.cells/ipagesavingcallback#pageEndSaving(com.aspose.cells.PageEndSavingArgs))** methods that you can implement in your custom class. You may also control which pages are rendered as demonstrated in the *TestTiffPageSavingCallback* custom class.

## **Track Conversion Progress of Excel to TIFF**

The following code sample loads the [source excel file](sampleUseWorkbookRenderForImageConversion.xlsx) and prints its conversion progress in the console by using the *TestTiffPageSavingCallback* custom class that implements the **[IPageSavingCallback](https://apireference.aspose.com/cells/java/com.aspose.cells/IPageSavingCallback)** interface. The generated output file is attached for your reference.

[Output File](DocumentConversionProgressForTiff_out.tiff)

## **Sample Code**

{{< gist "aspose-com-gists" "439a68a5e4305388c50ca306ef238de5" "Examples-src-AsposeCellsExamples-LoadingSavingConvertingAndManaging-DocumentConversionProgressForTiff-1.java" >}}

The following is the code for the *TestTiffPageSavingCallback* custom class.

{{< gist "aspose-com-gists" "439a68a5e4305388c50ca306ef238de5" "Examples-src-AsposeCellsExamples-LoadingSavingConvertingAndManaging-DocumentConversionProgressForTiff-2.java" >}}

## **Console Output**

Start saving page index 0 of pages 10</br>
End saving page index 0 of pages 10</br>
Start saving page index 1 of pages 10</br>
End saving page index 1 of pages 10</br>
Start saving page index 2 of pages 10</br>
End saving page index 2 of pages 10</br>
Start saving page index 3 of pages 10</br>
End saving page index 3 of pages 10</br>
Start saving page index 4 of pages 10</br>
End saving page index 4 of pages 10</br>
Start saving page index 5 of pages 10</br>
End saving page index 5 of pages 10</br>
Start saving page index 6 of pages 10</br>
End saving page index 6 of pages 10</br>
Start saving page index 7 of pages 10</br>
End saving page index 7 of pages 10</br>
Start saving page index 8 of pages 10</br>
End saving page index 8 of pages 10
