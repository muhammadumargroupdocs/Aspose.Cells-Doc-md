---
title: Optimizing Memory Usage while Working with Big Files having Large Datasets
type: docs
weight: 180
url: /net/optimizing-memory-usage-while-working-with-big-files-having-large-datasets/
---

{{% alert color="primary" %}} 

When building a workbook with large data sets, or reading a big Microsoft Excel file, the total amount of RAM the process will take is always a concern. There are measures that can be adapted to cope with the challenge. Aspose.Cells provides some relevant options and API calls to lower, reduce and optimize memory use. Also, it can help the process work more efficiently and run faster.

Use the [MemorySetting](https://apireference.aspose.com/net/cells/aspose.cells/memorysetting).MemoryPreference option to optimize memory use for cells data and decrease the overall memory cost. When building a large data set for cells, it can save a certain amount of memory compared to using the default setting ([MemorySetting](https://apireference.aspose.com/net/cells/aspose.cells/memorysetting).Normal).

{{% /alert %}} 
## **Optimizing Memory**
### **Reading Large Excel Files**
The following example shows how to read a large Microsoft Excel file in optimized mode.



{{< gist "aspose-com-gists" "24a8eac23c3325e20dababecf735a43b" "Examples-CSharp-Articles-OptimizingMemoryUsage-ReadingLargeExcelFiles-1.cs" >}}
### **Writing Large Excel Files**
The following example shows how to write a large dataset to a worksheet in an optimized mode.



{{< gist "aspose-com-gists" "24a8eac23c3325e20dababecf735a43b" "Examples-CSharp-Articles-OptimizingMemoryUsage-WritingLargeExcelFiles-1.cs" >}}
## **Caution**
The default option, [MemorySetting](https://apireference.aspose.com/net/cells/aspose.cells/memorysetting).Normal is applied for all versions. For some situations, such as building a workbook with a large data set for cells, the [MemorySetting](https://apireference.aspose.com/net/cells/aspose.cells/memorysetting).MemoryPreference option may optimize the memory use and decrease the memory cost for the application. However, this option may degrade performance in some special cases such as follow.

1. **Accessing Cells Randomly and Repeatedly**: The most efficient sequence for accessing the cells collection is cell by cell in one row, and then row by row. Especially, if you access rows/cells by the Enumerator acquired from [Cells](https://apireference.aspose.com/net/cells/aspose.cells/cells), [RowCollection](https://apireference.aspose.com/net/cells/aspose.cells/rowcollection) and [Row](https://apireference.aspose.com/net/cells/aspose.cells/row), the performance would be maximized with [MemorySetting](https://apireference.aspose.com/net/cells/aspose.cells/memorysetting).MemoryPreference.
1. **Inserting & Deleting Cells & Rows**: Please note that if there are lots of insert/delete operations for Cells/Rows, the performance degradation will be notable for *MemoryPreference* mode as compared to the *Normal* mode.
1. **Operating on Different Cell Types**: If most of the cells contain string values or formulas, the memory cost will be the same as *Normal* mode but if there are lots of empty cells, or cell values are numeric, bool and so on, the [MemorySetting](https://apireference.aspose.com/net/cells/aspose.cells/memorysetting).MemoryPreference option will give better performance.