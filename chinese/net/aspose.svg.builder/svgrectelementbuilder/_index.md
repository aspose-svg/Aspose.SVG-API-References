---
title: "SVGRectElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGRectElementBuilder 类。用于构建 SVG rect 元素的生成器类。rect 元素用于在 SVG 图形中创建矩形。此类提供设置 rect 元素特定属性的方法，包括角半径和尺寸。"
type: docs
weight: 1580
url: /zh/net/aspose.svg.builder/svgrectelementbuilder/
---
## SVGRectElementBuilder class

用于构建 SVG 'rect' 元素的构建器类。'rect' 元素用于在 SVG 图形中创建矩形。此类提供设置 'rect' 元素特定属性的方法，包括圆角半径和尺寸。

```csharp
public class SVGRectElementBuilder : SVGElementBuilder<SVGRectElement>, IAnimationElementBuilder, 
    IDescriptiveElementBuilder, IPaintServerElementBuilder, IRectAttributeSetter, 
    IShapeAttributeSetter, IShapeContentElementBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGRectElementBuilder](svgrectelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGRectElement](../../aspose.svg/svgrectelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Rx](../../aspose.svg.builder/svgrectelementbuilder/rx/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'rect' 元素的 'rx' 属性，指定矩形圆角的水平半径。 |
| [Ry](../../aspose.svg.builder/svgrectelementbuilder/ry/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'rect' 元素的 'ry' 属性，指定矩形圆角的垂直半径。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGRectElement](../../aspose.svg/svgrectelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IShapeAttributeSetter](../ishapeattributesetter/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
