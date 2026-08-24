---
title: "SVGFEGaussianBlurElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGFEGaussianBlurElementBuilder 类。用于创建应用高斯模糊滤镜效果的 SVG feGaussianBlur 元素的构建器类"
type: docs
weight: 1330
url: /zh/net/aspose.svg.builder/svgfegaussianblurelementbuilder/
---
## SVGFEGaussianBlurElementBuilder class

用于创建 SVG 'feGaussianBlur' 元素的构建器类，用于应用高斯模糊滤镜效果。

```csharp
public class SVGFEGaussianBlurElementBuilder : SVGElementBuilder<SVGFEGaussianBlurElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGFEGaussianBlurElementBuilder](svgfegaussianblurelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfegaussianblurelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 向 feGaussianBlur 元素添加脚本配置。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEGaussianBlurElement](../../aspose.svg.filters/svgfegaussianblurelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [StdDeviation](../../aspose.svg.builder/svgfegaussianblurelementbuilder/stddeviation/)(*double, double?*) | 设置高斯模糊效果的标准差。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEGaussianBlurElement](../../aspose.svg.filters/svgfegaussianblurelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
