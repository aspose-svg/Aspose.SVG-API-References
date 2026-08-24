---
title: "SVGTextElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGTextElementBuilder 类。用于创建 SVGTextElement 的构建器类，该元素用于在 SVG 文档中定义文本"
type: docs
weight: 1670
url: /zh/net/aspose.svg.builder/svgtextelementbuilder/
---
## SVGTextElementBuilder class

用于创建 SVGTextElement 的构建器类，该元素用于在 SVG 文档中定义文本。

```csharp
public class SVGTextElementBuilder : SVGElementBuilder<SVGTextElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPaintServerElementBuilder, 
    IShapeContentElementBuilder, ITextContentPositioningAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGTextElementBuilder](svgtextelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtextelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | 向文本元素添加一个 'a'（锚点）元素，以实现文本部分的超链接。 |
| [AddTextPath](../../aspose.svg.builder/svgtextelementbuilder/addtextpath/)(*Action&lt;SVGTextPathElementBuilder&gt;*) | 向文本元素添加一个 'textPath' 元素，使文本能够沿定义的路径排列。 |
| [AddTSpan](../../aspose.svg.builder/svgtextelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | 向文本元素添加一个 'tspan' 元素，以便对文本的各个部分进行细致控制。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTextElement](../../aspose.svg/svgtextelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGTextElement](../../aspose.svg/svgtextelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../itextcontentpositioningattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
