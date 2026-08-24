---
title: "SVGClipPathElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGClipPathElementBuilder 类。用于构建 SVG clipPath 元素的生成器类，该元素用于定义裁剪路径。它支持在 clipPath 元素内部构建内容，并提供设置 SVG 中 clipPath 元素特定属性的各种方法。"
type: docs
weight: 1130
url: /zh/net/aspose.svg.builder/svgclippathelementbuilder/
---
## SVGClipPathElementBuilder class

用于构建 SVG 'clipPath' 元素的构建器类，该元素用于定义剪裁路径。它支持在 'clipPath' 元素内构建内容，并提供设置 SVG 中 'clipPath' 元素特定属性的方法。

```csharp
public class SVGClipPathElementBuilder : SVGElementBuilder<SVGClipPathElement>, 
    IAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IShapeElementBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGClipPathElementBuilder](svgclippathelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgclippathelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 向 clipPath 元素添加一个 script 元素。 |
| [AddText](../../aspose.svg.builder/svgclippathelementbuilder/addtext/)(*Action&lt;SVGTextElementBuilder&gt;*) | 向 clipPath 元素添加一个 text 元素。 |
| [AddUse](../../aspose.svg.builder/svgclippathelementbuilder/adduse/)(*Action&lt;SVGUseElementBuilder&gt;*) | 向 clipPath 元素添加一个 'use' 元素。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGClipPathElement](../../aspose.svg/svgclippathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ClipPathUnits](../../aspose.svg.builder/svgclippathelementbuilder/clippathunits/)(*[CoordinateUnits](../coordinateunits/)*) | 设置 SVG 'clipPath' 元素的 'clipPathUnits' 属性，指定裁剪路径的坐标系统。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGClipPathElement](../../aspose.svg/svgclippathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IShapeElementBuilder](../ishapeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
