---
title: "SVGFEComponentTransferElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGFEComponentTransferElementBuilder 类。用于创建 SVG 过滤器中使用的 feComponentTransfer 元素的构建器类。"
type: docs
weight: 1210
url: /zh/net/aspose.svg.builder/svgfecomponenttransferelementbuilder/
---
## SVGFEComponentTransferElementBuilder class

用于创建 SVG 'feComponentTransfer' 元素的构建器类，用于 SVG 滤镜。

```csharp
public class SVGFEComponentTransferElementBuilder : 
    SVGElementBuilder<SVGFEComponentTransferElement>, ICoreAttributeSetter, 
    IDescriptiveElementBuilder, IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGFEComponentTransferElementBuilder](svgfecomponenttransferelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | 使用配置的组件传输函数构建 SVGFEComponentTransferElement。 |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEComponentTransferElement](../../aspose.svg.filters/svgfecomponenttransferelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [WithFeFuncA](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefunca/)(*Action&lt;SVGFEFuncAElementBuilder&gt;*) | 为 alpha 通道配置 'feFuncA' 组件传输函数。 |
| [WithFeFuncB](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefuncb/)(*Action&lt;SVGFEFuncBElementBuilder&gt;*) | 为 blue 通道配置 'feFuncB' 组件传输函数。 |
| [WithFeFuncG](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefuncg/)(*Action&lt;SVGFEFuncGElementBuilder&gt;*) | 为 green 通道配置 'feFuncG' 组件传输函数。 |
| [WithFeFuncR](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefuncr/)(*Action&lt;SVGFEFuncRElementBuilder&gt;*) | 为 red 通道配置 'feFuncR' 组件传输函数。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEComponentTransferElement](../../aspose.svg.filters/svgfecomponenttransferelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
