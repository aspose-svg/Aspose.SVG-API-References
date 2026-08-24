---
title: "SVGCircleElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGCircleElementBuilder 类。用于构建 SVG 圆形元素的生成器类，该元素用于在 SVG 图形中绘制圆形。它支持在 circle 元素内部构建内容，并提供设置 SVG 中 circle 元素特定属性的方法。"
type: docs
weight: 1120
url: /zh/net/aspose.svg.builder/svgcircleelementbuilder/
---
## SVGCircleElementBuilder class

用于构建 SVG 'circle' 元素的构建器类，该元素用于在 SVG 图形中绘制圆形。它支持在 'circle' 元素内构建内容，并提供设置 SVG 中 'circle' 元素特定属性的方法。

```csharp
public class SVGCircleElementBuilder : SVGElementBuilder<SVGCircleElement>, 
    IAnimationElementBuilder, IDescriptiveElementBuilder, IPaintServerElementBuilder, 
    IShapeAttributeSetter, IShapeContentElementBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGCircleElementBuilder](svgcircleelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGCircleElement](../../aspose.svg/svgcircleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Cx](../../aspose.svg.builder/svgcircleelementbuilder/cx/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'circle' 元素的 'cx' 属性，指定圆心的 x 坐标。 |
| [Cy](../../aspose.svg.builder/svgcircleelementbuilder/cy/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'circle' 元素的 'cy' 属性，指定圆心的 y 坐标。 |
| [R](../../aspose.svg.builder/svgcircleelementbuilder/r/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'circle' 元素的 'r' 属性，指定圆的半径。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGCircleElement](../../aspose.svg/svgcircleelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeAttributeSetter](../ishapeattributesetter/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
