---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGListBase InsertItemBefore 方法。在列表中指定位置插入一个新项。第一个项的编号为 0"
type: docs
weight: 90
url: /zh/net/aspose.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase<T>.InsertItemBefore method

在列表中指定位置插入一个新项。第一个项的编号为 0。

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newItem | T | 要插入到列表中的项。 |
| 索引 | UInt64 | 要在其前插入新项的项的索引。第一个项的编号为 0。如果索引等于 0，则新项插入到列表前端。如果索引大于或等于 numberOfItems，则新项追加到列表末尾。 |

### 返回值

插入的项。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/)。当列表无法被修改时抛出此错误。 |

### 另请参阅

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
