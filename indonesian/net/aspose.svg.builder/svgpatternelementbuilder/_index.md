---
title: "Kelas SVGPatternElementBuilder"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Kelas Aspose.Svg.Builder.SVGPatternElementBuilder. Kelas pembangun untuk membuat elemen pola SVG yang digunakan untuk mendefinisikan pola yang akan digunakan untuk mengisi elemen grafis dalam SVG. Kelas ini menyediakan metode untuk mengatur berbagai atribut khusus elemen pola dan untuk membangun isinya."
type: docs
weight: 1540
url: /id/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

Kelas Builder untuk membangun elemen SVG 'pattern', yang digunakan untuk mendefinisikan pola yang akan digunakan untuk mengisi elemen grafis dalam SVG. Kelas ini menyediakan metode untuk mengatur berbagai atribut khusus elemen 'pattern' dan untuk membangun kontennya.

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | Mengatur atribut 'href' pada elemen SVG 'pattern', menentukan referensi ke pola lain yang atributnya diwarisi oleh pola ini. |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Mengatur atribut 'patternContentUnits' pada elemen SVG 'pattern', menentukan sistem koordinat untuk isi pola. |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | Mengatur atribut 'patternTransform' pada elemen SVG 'pattern', menerapkan transformasi pada pola. |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | Mengatur atribut 'patternUnits' pada elemen SVG 'pattern', menentukan sistem koordinat untuk x, y, lebar, dan tinggi pola. |

### Lihat Juga

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPatternElement](../../aspose.svg/svgpatternelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
