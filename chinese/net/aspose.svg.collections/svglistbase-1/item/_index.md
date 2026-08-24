---
title: "SVGListBase-1.Item"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGListBase Item 属性。返回列表中第 index 项。"
type: docs
weight: 10
url: /zh/net/aspose.svg.collections/svglistbase-1/item/
---
## SVGListBase<T> indexer

返回列表中第 index 项。

```csharp
public T this[ulong index] { get; set; }
```

| 参数 | 描述 |
| --- | --- |
| 索引 | 列表中的索引。 |

### 返回值

列表中第 index 位置存储的对象。

### Property Value

列表中存储的项的类型。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/)。当列表无法被修改时抛出此错误。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/)。如果索引号大于或等于 numberOfItems，则抛出此错误。 |

### 另请参阅

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
