---
title: "SVGListBase-1.RemoveItem"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGListBase RemoveItem 方法。移除列表中已有的项。"
type: docs
weight: 100
url: /zh/net/aspose.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase<T>.RemoveItem method

从列表中移除现有的项。

```csharp
public T RemoveItem(ulong index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | UInt64 | 要移除的项的索引。第一个项的索引为 0。 |

### 返回值

被移除的项。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/)。当列表无法被修改时抛出此错误。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/)。如果索引号大于或等于 numberOfItems，则抛出此错误。 |

### 另请参阅

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
