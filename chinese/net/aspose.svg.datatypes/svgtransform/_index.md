---
title: "SVGTransform 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.DataTypes.SVGTransform 类。SVGTransform 是 SVGTransformList 中的一个组件变换的接口，因此 SVGTransform 对象对应于 transform 属性规范中的单个组件，例如 scale 或 matrix"
type: docs
weight: 2310
url: /zh/net/aspose.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform 是 SVGTransformList 中组件变换之一的接口；因此，SVGTransform 对象对应于 ‘transform’ 属性规范中的单个组件（例如 'scale(…)' 或 'matrix(…)')。

```csharp
public class SVGTransform : SVGValueType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Angle](../../aspose.svg.datatypes/svgtransform/angle/) { get; } | 一个用于 SVG_TRANSFORM_ROTATE、SVG_TRANSFORM_SKEWX 和 SVG_TRANSFORM_SKEWY 的便利属性。它保存指定的角度。对于 SVG_TRANSFORM_MATRIX、SVG_TRANSFORM_TRANSLATE 和 SVG_TRANSFORM_SCALE，角度将为零。 |
| [Matrix](../../aspose.svg.datatypes/svgtransform/matrix/) { get; } | 表示此变换的矩阵。矩阵对象是实时的，这意味着对 SVGTransform 对象所做的任何更改会立即反映在矩阵对象中，反之亦然。如果直接更改矩阵对象（即不使用 SVGTransform 接口本身的方法），则 SVGTransform 的类型会变为 SVG_TRANSFORM_MATRIX。对于 SVG_TRANSFORM_MATRIX，矩阵包含用户提供的 a、b、c、d、e、f 值。对于 SVG_TRANSFORM_TRANSLATE，e 和 f 表示平移量（a=1，b=0，c=0，d=1）。对于 SVG_TRANSFORM_SCALE，a 和 d 表示缩放量（b=0，c=0，e=0，f=0）。对于 SVG_TRANSFORM_SKEWX 和 SVG_TRANSFORM_SKEWY，a、b、c、d 表示将产生给定倾斜的矩阵（e=0，f=0）。对于 SVG_TRANSFORM_ROTATE，a、b、c、d、e、f 共同表示将产生给定旋转的矩阵。当旋转围绕中心点 (0, 0) 时，e 和 f 为零。 |
| [Type](../../aspose.svg.datatypes/svgtransform/type/) { get; } | 此接口上定义的 SVG_TRANSFORM_* 常量之一指定的值的类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [SetMatrix](../../aspose.svg.datatypes/svgtransform/setmatrix/)(*[SVGMatrix](../svgmatrix/)*) | 将变换类型设置为 SVG_TRANSFORM_MATRIX，参数 matrix 定义新的变换。参数 matrix 的值会被复制，matrix 参数不会替换 SVGTransform::matrix。 |
| [SetRotate](../../aspose.svg.datatypes/svgtransform/setrotate/)(*float, float, float*) | 将变换类型设置为 SVG_TRANSFORM_ROTATE，参数 angle 定义旋转角度，参数 cx 和 cy 定义可选的旋转中心。 |
| [SetScale](../../aspose.svg.datatypes/svgtransform/setscale/)(*float, float*) | 将变换类型设置为 SVG_TRANSFORM_SCALE，参数 sx 和 sy 定义缩放量。 |
| [SetSkewX](../../aspose.svg.datatypes/svgtransform/setskewx/)(*float*) | 将变换类型设置为 SVG_TRANSFORM_SKEWX，参数 angle 定义倾斜量。 |
| [SetSkewY](../../aspose.svg.datatypes/svgtransform/setskewy/)(*float*) | 将变换类型设置为 SVG_TRANSFORM_SKEWY，参数 angle 定义倾斜量。 |
| [SetTranslate](../../aspose.svg.datatypes/svgtransform/settranslate/)(*float, float*) | 将变换类型设置为 SVG_TRANSFORM_TRANSLATE，参数 tx 和 ty 定义平移量。 |
| override [ToString](../../aspose.svg.datatypes/svgtransform/tostring/)() | 返回表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.svg.datatypes/svgtransform/svg_transform_matrix/) | 一个 'matrix(…)' 变换。 |
| const [SVG_TRANSFORM_ROTATE](../../aspose.svg.datatypes/svgtransform/svg_transform_rotate/) | 一个 'rotate(…)' 变换。 |
| const [SVG_TRANSFORM_SCALE](../../aspose.svg.datatypes/svgtransform/svg_transform_scale/) | 一个 'scale(…)' 变换。 |
| const [SVG_TRANSFORM_SKEWX](../../aspose.svg.datatypes/svgtransform/svg_transform_skewx/) | 一个 'skewX(…)' 变换。 |
| const [SVG_TRANSFORM_SKEWY](../../aspose.svg.datatypes/svgtransform/svg_transform_skewy/) | 一个 'skewY(…)' 变换。 |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.svg.datatypes/svgtransform/svg_transform_translate/) | 一个 'translate(…)' 变换。 |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.svg.datatypes/svgtransform/svg_transform_unknown/) | 该单位类型不是预定义类型之一。尝试定义此类型的新值或尝试将现有值切换为此类型都是无效的。 |

### 另请参阅

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
