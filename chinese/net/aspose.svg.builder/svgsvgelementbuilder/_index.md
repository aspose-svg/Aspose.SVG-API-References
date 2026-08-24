---
title: "SVGSVGElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGSVGElementBuilder 类。用于创建 SVGSVGElement（SVG 文档的根元素）的构建器类"
type: docs
weight: 1590
url: /zh/net/aspose.svg.builder/svgsvgelementbuilder/
---
## SVGSVGElementBuilder class

用于创建 SVGSVGElement（SVG 文档根元素）的构建器类。

```csharp
public class SVGSVGElementBuilder : SVGElementBuilder<SVGSVGElement>, ICompositeAttributeSetter, 
    ICompositeElementBuilder, IDocumentEventAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter, IViewBoxAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGSVGElementBuilder](svgsvgelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| [BaseProfile](../../aspose.svg.builder/svgsvgelementbuilder/baseprofile/)(*double*) | 设置 SVG 元素的 'baseProfile' 属性。此属性指示文档适用的完整 SVG 规范的哪个子集。 |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSVGElement](../../aspose.svg/svgsvgelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ContentScriptType](../../aspose.svg.builder/svgsvgelementbuilder/contentscripttype/)(*string*) | 设置 SVG 元素的 'contentScriptType' 属性。此属性指定 SVG 文档内容的默认脚本语言。 |
| [ContentStyleType](../../aspose.svg.builder/svgsvgelementbuilder/contentstyletype/)(*string*) | 设置 SVG 元素的 'contentStyleType' 属性。此属性指定 SVG 文档内容的默认样式语言。 |
| [Version](../../aspose.svg.builder/svgsvgelementbuilder/version/)(*double*) | 设置 SVG 元素的 'version' 属性。此属性指定文档符合的 SVG 规范版本。 |
| [WithXlink](../../aspose.svg.builder/svgsvgelementbuilder/withxlink/)() | 向 SVG 元素添加 XLink 命名空间声明。这对于使用诸如 'xlink:href' 的 XLink 属性是必要的。 |
| [ZoomAndPan](../../aspose.svg.builder/svgsvgelementbuilder/zoomandpan/)(*string*) | 设置 SVG 元素的 'zoomAndPan' 属性。此属性控制 SVG 内容是否可以缩放和平移。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGSVGElement](../../aspose.svg/svgsvgelement/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IDocumentEventAttributeSetter](../idocumenteventattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
