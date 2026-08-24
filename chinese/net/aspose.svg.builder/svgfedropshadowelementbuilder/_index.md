---
title: "SVGFEDropShadowElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGFEDropShadowElementBuilder 类。用于创建 SVG feDropShadow 元素的生成器类，该元素在 SVG 滤镜中用于应用投影效果"
type: docs
weight: 1270
url: /zh/net/aspose.svg.builder/svgfedropshadowelementbuilder/
---
## SVGFEDropShadowElementBuilder class

用于创建 SVG 'feDropShadow' 元素的构建器类，用于 SVG 滤镜中应用投影阴影效果。

```csharp
public class SVGFEDropShadowElementBuilder : SVGElementBuilder<SVGFEDropShadowElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGFEDropShadowElementBuilder](svgfedropshadowelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfedropshadowelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 向 feDropShadow 元素添加脚本配置。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEDropShadowElement](../../aspose.svg.filters/svgfedropshadowelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Dx](../../aspose.svg.builder/svgfedropshadowelementbuilder/dx/)(*double*) | 设置投影的水平偏移（'dx'）。 |
| [Dy](../../aspose.svg.builder/svgfedropshadowelementbuilder/dy/)(*double*) | 设置投影的垂直偏移（'dy'）。 |
| [StdDeviation](../../aspose.svg.builder/svgfedropshadowelementbuilder/stddeviation/)(*double, double?*) | 设置投影模糊效果的标准差。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEDropShadowElement](../../aspose.svg.filters/svgfedropshadowelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
