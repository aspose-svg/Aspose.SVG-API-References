---
title: "SVGTransform.SetMatrix"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGTransform SetMatrix 方法。将变换类型设置为 SVG_TRANSFORM_MATRIX，参数 matrix 定义新的变换。参数 matrix 的值会被复制，matrix 参数不会替换 SVGTransformmatrix"
type: docs
weight: 40
url: /zh/net/aspose.svg.datatypes/svgtransform/setmatrix/
---
## SVGTransform.SetMatrix method

将变换类型设置为 SVG_TRANSFORM_MATRIX，参数 matrix 定义新的变换。参数 matrix 的值会被复制，matrix 参数不会替换 SVGTransform::matrix。

```csharp
public void SetMatrix(SVGMatrix matrix)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩阵 | SVGMatrix | 用于变换的新矩阵。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/)。在尝试更改只读属性的值时抛出。 |

### 另请参阅

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
