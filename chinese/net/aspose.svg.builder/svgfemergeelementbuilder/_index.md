---
title: "SVGFEMergeElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGFEMergeElementBuilder 类。用于创建 SVG feMerge 元素的构建器类，这些元素用于合成图像或图像的部分"
type: docs
weight: 1350
url: /zh/net/aspose.svg.builder/svgfemergeelementbuilder/
---
## SVGFEMergeElementBuilder class

用于创建 SVG 'feMerge' 元素的构建器类，用于将图像或图像的部分合成在一起。

```csharp
public class SVGFEMergeElementBuilder : SVGElementBuilder<SVGFEMergeElement>, ICoreAttributeSetter, 
    IDescriptiveElementBuilder, IFilterPrimitiveAttributeSetter, IPresentationAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGFEMergeElementBuilder](svgfemergeelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddMergeNode](../../aspose.svg.builder/svgfemergeelementbuilder/addmergenode/)(*Action&lt;SVGFEMergeNodeElementBuilder&gt;*) | 向 feMerge 元素添加合并节点配置。 |
| [AddScript](../../aspose.svg.builder/svgfemergeelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 向 feMerge 元素添加脚本配置。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEMergeElement](../../aspose.svg.filters/svgfemergeelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEMergeElement](../../aspose.svg.filters/svgfemergeelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveAttributeSetter](../ifilterprimitiveattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
