---
title: "SVGTSpanElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGTSpanElementBuilder 类。用于创建 SVGTSpanElement 的生成器类，SVGTSpanElement 用于在 SVG 文档中定位和样式化文本。"
type: docs
weight: 1660
url: /zh/net/aspose.svg.builder/svgtspanelementbuilder/
---
## SVGTSpanElementBuilder class

用于创建 SVGTSpanElement 的构建器类，该类用于在 SVG 文档中定位和样式化文本。

```csharp
public class SVGTSpanElementBuilder : SVGElementBuilder<SVGTSpanElement>, 
    IBaseAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IPaintServerElementBuilder, ITextContentPositioningAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGTSpanElementBuilder](svgtspanelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtspanelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | 向当前 tspan 元素添加一个锚点 (a) 元素。 |
| [AddScript](../../aspose.svg.builder/svgtspanelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 向当前 tspan 元素添加一个 script 元素。 |
| [AddStyle](../../aspose.svg.builder/svgtspanelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | 向当前 tspan 元素添加一个 style 元素。 |
| [AddTSpan](../../aspose.svg.builder/svgtspanelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | 向当前 tspan 元素添加一个嵌套的 tspan 元素。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTSpanElement](../../aspose.svg/svgtspanelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGTSpanElement](../../aspose.svg/svgtspanelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../itextcontentpositioningattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
