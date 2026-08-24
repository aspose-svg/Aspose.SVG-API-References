---
title: "SVGFEImageElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGFEImageElementBuilder 类。用于创建 SVG feImage 元素的生成器类，这些元素定义了供其他滤镜原语使用的图像。"
type: docs
weight: 1340
url: /zh/net/aspose.svg.builder/svgfeimageelementbuilder/
---
## SVGFEImageElementBuilder class

用于创建 SVG 'feImage' 元素的构建器类，用于定义供其他滤镜基元使用的图像。

```csharp
public class SVGFEImageElementBuilder : SVGElementBuilder<SVGFEImageElement>, 
    IAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveAttributeSetter, IPresentationAttributeSetter, 
    IPreserveAspectRatioAttributeSetter, IXLinkAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGFEImageElementBuilder](svgfeimageelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svgfeimageelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | 向 feImage 元素添加动画变换配置。 |
| [AddScript](../../aspose.svg.builder/svgfeimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 向 feImage 元素添加脚本配置。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEImageElement](../../aspose.svg.filters/svgfeimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgfeimageelementbuilder/href/)(*string*) | 设置 feImage 元素的 'href' 属性，定义要使用的图像 URL。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEImageElement](../../aspose.svg.filters/svgfeimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveAttributeSetter](../ifilterprimitiveattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IXLinkAttributeSetter](../ixlinkattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
