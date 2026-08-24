---
title: "SVGListBase-1.GetItem"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGListBase GetItem 方法。返回列表中指定的项。"
type: docs
weight: 70
url: /zh/net/aspose.svg.collections/svglistbase-1/getitem/
---
## SVGListBase<T>.GetItem method

返回列表中指定的项。

```csharp
public T GetItem(ulong index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | UInt64 | 要返回的列表中项的索引。第一个项的索引为 0。 |

### 返回值

选定的项。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/)。如果索引号大于或等于 numberOfItems，则抛出此错误。 |

### 另请参阅

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
