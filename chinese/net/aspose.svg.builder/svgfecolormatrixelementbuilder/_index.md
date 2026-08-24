---
title: "SVGFEColorMatrixElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGFEColorMatrixElementBuilder 类。用于创建 SVG 滤镜中使用的 feColorMatrix 元素的构建器类"
type: docs
weight: 1200
url: /zh/net/aspose.svg.builder/svgfecolormatrixelementbuilder/
---
## SVGFEColorMatrixElementBuilder class

用于创建 SVG 'feColorMatrix' 元素的构建器类，用于 SVG 滤镜。

```csharp
public class SVGFEColorMatrixElementBuilder : SVGElementBuilder<SVGFEColorMatrixElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGFEColorMatrixElementBuilder](svgfecolormatrixelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfecolormatrixelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 向 feColorMatrix 元素添加脚本配置。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEColorMatrixElement](../../aspose.svg.filters/svgfecolormatrixelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [TypeAndValues](../../aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/)(*[ColorMatrixOperation](../colormatrixoperation/), params double[]*) | 设置 feColorMatrix 元素的 'type' 和 'values' 属性，指定颜色矩阵操作及其参数。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEColorMatrixElement](../../aspose.svg.filters/svgfecolormatrixelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
