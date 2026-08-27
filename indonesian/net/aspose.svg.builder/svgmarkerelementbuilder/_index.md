---
title: "SVGMarkerElementBuilder Class"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Aspose.Svg.Builder.SVGMarkerElementBuilder class. Kelas pembangun untuk membuat elemen SVG marker yang digunakan untuk mendefinisikan penanda grafis seperti kepala panah atau peluru yang dapat dilampirkan pada elemen path, line, polyline, dan polygon. Kelas ini memungkinkan pembuatan konten di dalam elemen marker dan menyediakan metode untuk mengatur berbagai atribut khusus elemen marker dalam SVG."
type: docs
weight: 1500
url: /id/net/aspose.svg.builder/svgmarkerelementbuilder/
---
## SVGMarkerElementBuilder class

Kelas Builder untuk membangun elemen SVG 'marker', yang digunakan untuk mendefinisikan penanda grafis, seperti ujung panah atau bullet, yang dapat dilampirkan pada elemen 'path', 'line', 'polyline', dan 'polygon'. Kelas ini memungkinkan pembuatan konten dalam elemen 'marker' dan menyediakan metode untuk mengatur berbagai atribut khusus elemen 'marker' dalam SVG.

```csharp
public class SVGMarkerElementBuilder : SVGElementBuilder<SVGMarkerElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRefCoordinatesAttributeSetter, IViewBoxAttributeSetter
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SVGMarkerElementBuilder](svgmarkerelementbuilder/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMarkerElement](../../aspose.svg/svgmarkerelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MarkerHeight](../../aspose.svg.builder/svgmarkerelementbuilder/markerheight/)(*double, [LengthType](../lengthtype/)*) | Mengatur atribut 'markerHeight' pada elemen SVG 'marker', yang menentukan tinggi viewport marker. |
| [MarkerUnits](../../aspose.svg.builder/svgmarkerelementbuilder/markerunits/)(*[MarkerUnits](../markerunits/)*) | Mengatur atribut 'markerUnits' pada elemen SVG 'marker', yang menentukan sistem koordinat untuk atribut marker. |
| [MarkerWidth](../../aspose.svg.builder/svgmarkerelementbuilder/markerwidth/)(*double, [LengthType](../lengthtype/)*) | Mengatur atribut 'markerWidth' pada elemen SVG 'marker', yang menentukan lebar viewport marker. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient)(*[Orient](../orient/)*) | Mengatur atribut 'orient' pada elemen SVG 'marker', yang menentukan orientasi marker. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient_1)(*double, [AngleUnits](../angleunits/)*) | Mengatur atribut 'orient' pada elemen SVG 'marker', yang menentukan sudut orientasi marker. |

### Lihat Juga

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
