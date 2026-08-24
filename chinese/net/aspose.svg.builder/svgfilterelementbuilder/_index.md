---
title: "SVGFilterElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGFilterElementBuilder 类。用于创建 SVG 滤镜元素的构建器类，这些元素定义可应用于 SVG 图形的滤镜效果"
type: docs
weight: 1440
url: /zh/net/aspose.svg.builder/svgfilterelementbuilder/
---
## SVGFilterElementBuilder class

用于创建 SVG 'filter' 元素的构建器类，这些元素定义可应用于 SVG 图形的滤镜效果。

```csharp
public class SVGFilterElementBuilder : SVGElementBuilder<SVGFilterElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IFilterPrimitiveElementBuilder, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IRectAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGFilterElementBuilder](svgfilterelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfilterelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 向滤镜元素添加脚本配置。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFilterElement](../../aspose.svg/svgfilterelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [FilterUnits](../../aspose.svg.builder/svgfilterelementbuilder/filterunits/)(*[CoordinateUnits](../coordinateunits/)*) | 设置滤镜的 x、y、宽度和高度属性的坐标系。 |
| [PrimitiveUnits](../../aspose.svg.builder/svgfilterelementbuilder/primitiveunits/)(*[CoordinateUnits](../coordinateunits/)*) | 设置滤镜的原始子元素的坐标系。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFilterElement](../../aspose.svg/svgfilterelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IFilterPrimitiveElementBuilder](../ifilterprimitiveelementbuilder/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
