---
title: "SVGTextPathElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGTextPathElementBuilder 类。用于创建 SVG textPath 元素的构建器类，这些元素用于将文本对齐到路径上。"
type: docs
weight: 1680
url: /zh/net/aspose.svg.builder/svgtextpathelementbuilder/
---
## SVGTextPathElementBuilder class

用于创建 SVG 'textPath' 元素的构建器类，这些元素用于将文本对齐到路径上。

```csharp
public class SVGTextPathElementBuilder : SVGElementBuilder<SVGTextPathElement>, 
    IBaseAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IPaintServerElementBuilder, IShapeContentElementBuilder, ITextContentSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGTextPathElementBuilder](svgtextpathelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtextpathelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | 向 'textPath' 添加一个 'a'（锚点）元素配置。 |
| [AddTSpan](../../aspose.svg.builder/svgtextpathelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | 向 'textPath' 添加一个 'tspan' 元素配置。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTextPathElement](../../aspose.svg/svgtextpathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgtextpathelementbuilder/href/)(*string*) | 设置 'href' 属性，指定对路径元素的引用。 |
| [LengthAdjust](../../aspose.svg.builder/svgtextpathelementbuilder/lengthadjust/)(*[LengthAdjust](../lengthadjust/)*) | 设置 'lengthAdjust' 属性，指定文本长度调整的方式。 |
| [Method](../../aspose.svg.builder/svgtextpathelementbuilder/method/)(*[TextPathMethod](../textpathmethod/)*) | 设置 'method' 属性，指定沿路径的文本布局方式。 |
| [Path](../../aspose.svg.builder/svgtextpathelementbuilder/path/)(*Action&lt;PathBuilder&gt;*) | 配置文本的路径。 |
| [Side](../../aspose.svg.builder/svgtextpathelementbuilder/side/)(*[HorizontalEdge](../horizontaledge/)*) | 设置 'side' 属性，指定文本放置在路径的哪一侧。 |
| [Spacing](../../aspose.svg.builder/svgtextpathelementbuilder/spacing/)(*[TextPathSpacing](../textpathspacing/)*) | 设置 'spacing' 属性，指定沿路径文本的间距策略。 |
| [StartOffset](../../aspose.svg.builder/svgtextpathelementbuilder/startoffset/)(*double, [LengthType](../lengthtype/)*) | 设置 'startOffset' 属性，指定文本在路径上的起始位置。 |
| [TextLength](../../aspose.svg.builder/svgtextpathelementbuilder/textlength/)(*double, [LengthType](../lengthtype/)*) | 设置 'textLength' 属性，指定文本的长度。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGTextPathElement](../../aspose.svg/svgtextpathelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* interface [ITextContentSetter](../itextcontentsetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
