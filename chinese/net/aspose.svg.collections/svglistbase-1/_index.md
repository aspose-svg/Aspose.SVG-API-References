---
title: "SVGListBaseT 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Collections.SVGListBase1T 类。此接口定义所有 SVG 列表的基础列表"
type: docs
weight: 2040
url: /zh/net/aspose.svg.collections/svglistbase-1/
---
## SVGListBase<T> class

此接口定义了所有 SVG 列表的基础列表。

```csharp
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| 参数 | 描述 |
| --- | --- |
| T | 列表中存储的项的类型。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Item](../../aspose.svg.collections/svglistbase-1/item/) { get; set; } | 返回列表中第 index 项。 |
| [Length](../../aspose.svg.collections/svglistbase-1/length/) { get; } | 列表中项的数量。 |
| [NumberOfItems](../../aspose.svg.collections/svglistbase-1/numberofitems/) { get; } | 列表中项的数量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AppendItem](../../aspose.svg.collections/svglistbase-1/appenditem/)(*T*) | 在列表末尾插入一个新项。 |
| [Clear](../../aspose.svg.collections/svglistbase-1/clear/)() | 清除列表中所有现有的当前项，结果是一个空列表。 |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [GetEnumerator](../../aspose.svg.collections/svglistbase-1/getenumerator/)() | 获取枚举器。 |
| [GetItem](../../aspose.svg.collections/svglistbase-1/getitem/)(*ulong*) | 返回列表中指定的项。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [Initialize](../../aspose.svg.collections/svglistbase-1/initialize/)(*T*) | 清除列表中所有现有的当前项，并重新初始化列表以容纳参数指定的单个项。 |
| [InsertItemBefore](../../aspose.svg.collections/svglistbase-1/insertitembefore/)(*T, ulong*) | 在列表中指定位置插入一个新项。第一个项的编号为 0。 |
| [RemoveItem](../../aspose.svg.collections/svglistbase-1/removeitem/)(*ulong*) | 从列表中移除现有的项。 |
| [ReplaceItem](../../aspose.svg.collections/svglistbase-1/replaceitem/)(*T, ulong*) | 用新项替换列表中现有的项。 |

### 另请参阅

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
