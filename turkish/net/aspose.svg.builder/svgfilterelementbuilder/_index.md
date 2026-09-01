---
title: "SVGFilterElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGFilterElementBuilder sınıfı. SVG grafiklerine uygulanabilen filtre efektlerini tanımlayan SVG filtre öğeleri oluşturmak için yapılandırıcı sınıf."
type: docs
weight: 1440
url: /tr/net/aspose.svg.builder/svgfilterelementbuilder/
---
## SVGFilterElementBuilder class

SVG 'filter' öğelerini oluşturmak için Builder sınıfı, SVG grafiklerine uygulanabilen filtre etkilerini tanımlar.

```csharp
public class SVGFilterElementBuilder : SVGElementBuilder<SVGFilterElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IFilterPrimitiveElementBuilder, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IRectAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGFilterElementBuilder](svgfilterelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfilterelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Filtre öğesine bir betik yapılandırması ekler. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFilterElement](../../aspose.svg/svgfilterelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [FilterUnits](../../aspose.svg.builder/svgfilterelementbuilder/filterunits/)(*[CoordinateUnits](../coordinateunits/)*) | Filtre'nin x, y, genişlik ve yükseklik öznitelikleri için koordinat sistemini ayarlar. |
| [PrimitiveUnits](../../aspose.svg.builder/svgfilterelementbuilder/primitiveunits/)(*[CoordinateUnits](../coordinateunits/)*) | Filtre'nin temel alt öğeleri için koordinat sistemini ayarlar. |

### Ayrıca Bakınız

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
