---
title: "SVGLineElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGLineElementBuilder 类。用于构建 SVG 线元素的构建器类，线元素用于在 SVG 图形中绘制直线。该类支持在 line 元素内构建内容，并提供方法设置 SVG 中 line 元素的各种特定属性。"
type: docs
weight: 1480
url: /zh/net/aspose.svg.builder/svglineelementbuilder/
---
## SVGLineElementBuilder class

用于构建 SVG 'line' 元素的构建器类，该元素用于在 SVG 图形中绘制直线。此类支持在 'line' 元素内构建内容，并提供设置该元素特定属性的各种方法。

```csharp
public class SVGLineElementBuilder : SVGElementBuilder<SVGLineElement>, IAnimationElementBuilder, 
    IDescriptiveElementBuilder, IPaintServerElementBuilder, IShapeAttributeSetter, 
    IShapeContentElementBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGLineElementBuilder](svglineelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGLineElement](../../aspose.svg/svglineelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [X1](../../aspose.svg.builder/svglineelementbuilder/x1/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'line' 元素的 'x1' 属性，指定线段起点的 x 坐标。 |
| [X2](../../aspose.svg.builder/svglineelementbuilder/x2/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'line' 元素的 'x2' 属性，指定线段终点的 x 坐标。 |
| [Y1](../../aspose.svg.builder/svglineelementbuilder/y1/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'line' 元素的 'y1' 属性，指定线段起点的 y 坐标。 |
| [Y2](../../aspose.svg.builder/svglineelementbuilder/y2/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'line' 元素的 'y2' 属性，指定线段终点的 y 坐标。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGLineElement](../../aspose.svg/svglineelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeAttributeSetter](../ishapeattributesetter/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
