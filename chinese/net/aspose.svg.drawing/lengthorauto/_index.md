---
title: "LengthOrAuto 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Drawing.LengthOrAuto 类。表示用于存储长度或自动单位的容器"
type: docs
weight: 3560
url: /zh/net/aspose.svg.drawing/lengthorauto/
---
## LengthOrAuto class

表示用于存储长度或 “auto” 单位的容器。

```csharp
public class LengthOrAuto : Unit
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LengthOrAuto](lengthorauto/#constructor)() | 初始化 `LengthOrAuto` 类的新实例，并将状态设置为 'auto'。 |
| [LengthOrAuto](lengthorauto/#constructor_1)(*[Length](../length/)*) | 初始化 `LengthOrAuto` 类的新实例，并将状态设置为 'lenght'。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IsAuto](../../aspose.svg.drawing/lengthorauto/isauto/) { get; } | 获取一个值，指示此实例是否处于 'auto' 状态。 |
| [Length](../../aspose.svg.drawing/lengthorauto/length/) { get; set; } | 获取或设置长度。 |
| [UnitType](../../aspose.svg.drawing/lengthorauto/unittype/) { get; } | 获取 [`Unit`](../unit/) 的单位类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.svg.drawing/unit/equals/)(*object*) | 确定指定的 Object 是否等于此实例。 |
| override [Equals](../../aspose.svg.drawing/lengthorauto/equals/#equals)(*[Unit](../unit/)*) | 确定指定的 [`Unit`](../unit/) 是否等于此实例。 |
| override [GetHashCode](../../aspose.svg.drawing/unit/gethashcode/)() | 返回此实例的哈希码。 |
| [SetAuto](../../aspose.svg.drawing/lengthorauto/setauto/)() | 将容器重置为 'auto' 状态。 |
| override [ToString](../../aspose.svg.drawing/lengthorauto/tostring/)() | 返回表示此实例的字符串。 |
| [implicit operator](../../aspose.svg.drawing/lengthorauto/op_implicit/) | 执行从 [`Length`](./length/) 到 `LengthOrAuto` 的隐式转换。 |

### 另请参阅

* class [Unit](../unit/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
