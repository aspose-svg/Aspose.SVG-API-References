---
title: "SVGMatrix 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.DataTypes.SVGMatrix 类。许多 SVG 图形操作使用形式为 a c e b d f 的 2x3 矩阵，在进行矩阵运算时会展开为 3x3 矩阵，变为 a c e b d f 0 0 1。"
type: docs
weight: 2230
url: /zh/net/aspose.svg.datatypes/svgmatrix/
---
## SVGMatrix class

许多 SVG 的图形操作使用以下形式的 2x3 矩阵： [a c e] [b d f]，在进行矩阵运算时会展开为 3x3 矩阵，变为： [a c e] [b d f] [0 0 1]

```csharp
public class SVGMatrix : SVGValueType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [A](../../aspose.svg.datatypes/svgmatrix/a/) { get; set; } | 矩阵的 A 分量。 |
| [B](../../aspose.svg.datatypes/svgmatrix/b/) { get; set; } | 矩阵的 B 分量。 |
| [C](../../aspose.svg.datatypes/svgmatrix/c/) { get; set; } | 矩阵的 C 分量。 |
| [D](../../aspose.svg.datatypes/svgmatrix/d/) { get; set; } | 矩阵的 D 分量。 |
| [E](../../aspose.svg.datatypes/svgmatrix/e/) { get; set; } | 矩阵的 E 分量。 |
| [F](../../aspose.svg.datatypes/svgmatrix/f/) { get; set; } | 矩阵的 F 分量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [Multiply](../../aspose.svg.datatypes/svgmatrix/multiply/)(*SVGMatrix*) | 执行矩阵乘法。此矩阵会被另一个矩阵后乘，返回结果新矩阵。 |
| [Rotate](../../aspose.svg.datatypes/svgmatrix/rotate/)(*float*) | 在当前矩阵上后乘一个旋转变换，并返回结果矩阵。 |
| [Scale](../../aspose.svg.datatypes/svgmatrix/scale/)(*float*) | 在当前矩阵上后乘一个统一缩放变换，并返回结果矩阵。 |
| [ScaleNonUniform](../../aspose.svg.datatypes/svgmatrix/scalenonuniform/)(*float, float*) | 在当前矩阵上后乘一个非统一缩放变换，并返回结果矩阵。 |
| [SkewX](../../aspose.svg.datatypes/svgmatrix/skewx/)(*float*) | 在当前矩阵上后乘一个 skewX 变换，并返回结果矩阵。 |
| [SkewY](../../aspose.svg.datatypes/svgmatrix/skewy/)(*float*) | 在当前矩阵上后乘一个 skewY 变换，并返回结果矩阵。 |
| override [ToString](../../aspose.svg.datatypes/svgmatrix/tostring/)() | 返回表示此实例的字符串。 |
| [Translate](../../aspose.svg.datatypes/svgmatrix/translate/)(*float, float*) | 在当前矩阵上后乘一个平移变换，并返回结果矩阵。 |

### 另请参阅

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
