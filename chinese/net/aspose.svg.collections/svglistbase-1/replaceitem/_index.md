---
title: "SVGListBase-1.ReplaceItem"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGListBase ReplaceItem 方法。用新项替换列表中已有的项"
type: docs
weight: 110
url: /zh/net/aspose.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase<T>.ReplaceItem method

用新项替换列表中现有的项。

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newItem | T | 要插入到列表中的项。 |
| 索引 | UInt64 | 要被替换的项的索引。第一个项的编号为 0。 |

### 返回值

插入的项。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/)。当列表无法被修改时抛出此错误。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/)。如果索引号大于或等于 numberOfItems，则抛出此错误。 |

### 另请参阅

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
