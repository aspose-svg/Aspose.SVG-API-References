---
title: "SVGRadialGradientElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGRadialGradientElementBuilder 类。用于构建 SVG radialGradient 元素的构建器类，该元素用于在 SVG 图形中定义径向渐变。此类能够在 radialGradient 元素内构建内容，并提供设置 SVG 中 radialGradient 元素特定属性的方法。"
type: docs
weight: 1570
url: /zh/net/aspose.svg.builder/svgradialgradientelementbuilder/
---
## SVGRadialGradientElementBuilder class

用于构建 SVG 'radialGradient' 元素的构建器类，该元素用于在 SVG 图形中定义径向渐变。此类支持在 'radialGradient' 元素内构建内容，并提供设置该元素特定属性的各种方法。

```csharp
public class SVGRadialGradientElementBuilder : SVGElementBuilder<SVGRadialGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGRadialGradientElementBuilder](svgradialgradientelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svgradialgradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | 向 SVG 'radialGradient' 元素添加动画变换配置。 |
| [AddScript](../../aspose.svg.builder/svgradialgradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 向 SVG 'radialGradient' 元素添加脚本配置。 |
| [AddStyle](../../aspose.svg.builder/svgradialgradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | 向 SVG 'radialGradient' 元素添加样式配置。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGRadialGradientElement](../../aspose.svg/svgradialgradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Cx](../../aspose.svg.builder/svgradialgradientelementbuilder/cx/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'radialGradient' 元素的 'cx' 属性，指定渐变中心的 x 坐标。 |
| [Cy](../../aspose.svg.builder/svgradialgradientelementbuilder/cy/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'radialGradient' 元素的 'cy' 属性，指定渐变中心的 y 坐标。 |
| [Fx](../../aspose.svg.builder/svgradialgradientelementbuilder/fx/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'radialGradient' 元素的 'fx' 属性，指定渐变焦点的 x 坐标。 |
| [Fy](../../aspose.svg.builder/svgradialgradientelementbuilder/fy/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'radialGradient' 元素的 'fy' 属性，指定渐变焦点的 y 坐标。 |
| [Href](../../aspose.svg.builder/svgradialgradientelementbuilder/href/)(*string*) | 设置 SVG 'radialGradient' 元素的 'href' 属性，指定对另一个渐变的引用。 |
| [R](../../aspose.svg.builder/svgradialgradientelementbuilder/r/)(*double, [LengthType](../lengthtype/)*) | 设置 SVG 'radialGradient' 元素的 'r' 属性，指定渐变的半径。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGRadialGradientElement](../../aspose.svg/svgradialgradientelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IGradientStopElementBuilder](../igradientstopelementbuilder/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
