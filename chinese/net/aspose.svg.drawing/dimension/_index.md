---
title: "Dimension 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Drawing.Dimension 类。提供维度的基类。一般术语维度指的是带有单位的数值，并由 UnitType 表示。"
type: docs
weight: 3410
url: /zh/net/aspose.svg.drawing/dimension/
---
## Dimension class

提供维度的基类。一般术语 'dimension' 指的是带有单位的数值，并由 [`UnitType`](../unittype/) 表示。

```csharp
public abstract class Dimension : Numeric
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [UnitType](../../aspose.svg.drawing/unit/unittype/) { get; } | 获取 [`Unit`](../unit/) 的单位类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../aspose.svg.drawing/numeric/compareto/)(*[Numeric](../numeric/)*) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例是在排序顺序中位于该对象之前、之后，还是相同位置。 |
| override [Equals](../../aspose.svg.drawing/unit/equals/)(*object*) | 确定指定的 Object 是否等于此实例。 |
| override [Equals](../../aspose.svg.drawing/numeric/equals/)(*[Unit](../unit/)*) | 确定指定的 [`Unit`](../unit/) 是否等于此实例。 |
| override [GetHashCode](../../aspose.svg.drawing/numeric/gethashcode/)() | 返回此实例的哈希码。 |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)() | 获取单位值。 |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)(*[UnitType](../unittype/)*) | 获取转换为指定的 [`UnitType`](../unittype/) 的值。 |
| override [ToString](../../aspose.svg.drawing/dimension/tostring/)() | 返回表示此实例的字符串。 |

### 另请参阅

* class [Unit](../unit/)
* class [Numeric](../numeric/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
