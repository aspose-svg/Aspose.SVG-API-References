---
title: "SVGFEColorMatrixElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGFEColorMatrixElementBuilder sınıfı. SVG filtrelerinde kullanılan SVG feColorMatrix öğelerini oluşturmak için yapılandırıcı sınıf."
type: docs
weight: 1200
url: /tr/net/aspose.svg.builder/svgfecolormatrixelementbuilder/
---
## SVGFEColorMatrixElementBuilder class

SVG 'feColorMatrix' öğelerini oluşturmak için oluşturucu sınıf, SVG filtrelerinde kullanılır.

```csharp
public class SVGFEColorMatrixElementBuilder : SVGElementBuilder<SVGFEColorMatrixElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGFEColorMatrixElementBuilder](svgfecolormatrixelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfecolormatrixelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feColorMatrix öğesine bir betik yapılandırması ekler. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEColorMatrixElement](../../aspose.svg.filters/svgfecolormatrixelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [TypeAndValues](../../aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/)(*[ColorMatrixOperation](../colormatrixoperation/), params double[]*) | feColorMatrix öğesinin 'type' ve 'values' özniteliklerini ayarlar, renk matrisi işlemini ve parametrelerini belirtir. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEColorMatrixElement](../../aspose.svg.filters/svgfecolormatrixelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
