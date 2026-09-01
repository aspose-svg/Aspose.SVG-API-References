---
title: "SVGMarkerElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGMarkerElementBuilder sınıf. SVG marker öğesini oluşturmak için kullanılan bir sınıf; bu öğe, yol, çizgi, çokgen ve poligon öğelerine eklenebilen ok başları veya madde imleri gibi grafik işaretçileri tanımlamak için kullanılır. Bu sınıf, marker öğesi içinde içerik oluşturmayı sağlar ve SVG'de marker öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sunar."
type: docs
weight: 1500
url: /tr/net/aspose.svg.builder/svgmarkerelementbuilder/
---
## SVGMarkerElementBuilder class

SVG 'marker' öğesini oluşturmak için Builder sınıfı, bu öğe ok uçları veya madde işaretleri gibi grafik işaretçileri tanımlamak ve 'path', 'line', 'polyline' ve 'polygon' öğelerine eklemek için kullanılır. 'marker' öğesi içinde içerik oluşturmayı sağlar ve SVG'de 'marker' öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sunar.

```csharp
public class SVGMarkerElementBuilder : SVGElementBuilder<SVGMarkerElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRefCoordinatesAttributeSetter, IViewBoxAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGMarkerElementBuilder](svgmarkerelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMarkerElement](../../aspose.svg/svgmarkerelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MarkerHeight](../../aspose.svg.builder/svgmarkerelementbuilder/markerheight/)(*double, [LengthType](../lengthtype/)*) | SVG 'marker' öğesinin 'markerHeight' özniteliğini ayarlar, işaretçinin görünüm alanının yüksekliğini belirtir. |
| [MarkerUnits](../../aspose.svg.builder/svgmarkerelementbuilder/markerunits/)(*[MarkerUnits](../markerunits/)*) | SVG 'marker' öğesinin 'markerUnits' özniteliğini ayarlar, işaretçinin öznitelikleri için koordinat sistemini belirtir. |
| [MarkerWidth](../../aspose.svg.builder/svgmarkerelementbuilder/markerwidth/)(*double, [LengthType](../lengthtype/)*) | SVG 'marker' öğesinin 'markerWidth' özniteliğini ayarlar, işaretçinin görünüm alanının genişliğini belirtir. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient)(*[Orient](../orient/)*) | SVG 'marker' öğesinin 'orient' özniteliğini ayarlar, işaretçinin yönünü belirtir. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient_1)(*double, [AngleUnits](../angleunits/)*) | SVG 'marker' öğesinin 'orient' özniteliğini ayarlar, işaretçinin yön açısını belirtir. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMarkerElement](../../aspose.svg/svgmarkerelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRefCoordinatesAttributeSetter](../irefcoordinatesattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
