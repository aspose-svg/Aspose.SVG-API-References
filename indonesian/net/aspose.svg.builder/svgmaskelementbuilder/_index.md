---
title: "Kelas SVGMaskElementBuilder"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Aspose.Svg.Builder.SVGMaskElementBuilder class. Kelas pembangun untuk membuat elemen mask SVG yang digunakan untuk mendefinisikan mask alfa untuk menggabungkan objek saat ini ke latar belakang. Kelas ini memungkinkan pembuatan konten di dalam elemen mask dan menyediakan metode untuk mengatur berbagai atribut khusus elemen mask dalam SVG."
type: docs
weight: 1510
url: /id/net/aspose.svg.builder/svgmaskelementbuilder/
---
## SVGMaskElementBuilder class

Kelas Builder untuk membangun elemen SVG 'mask', yang digunakan untuk mendefinisikan masker alfa untuk menggabungkan objek saat ini ke latar belakang. Kelas ini memungkinkan pembuatan konten dalam elemen 'mask' dan menyediakan metode untuk mengatur berbagai atribut khusus elemen 'mask' dalam SVG.

```csharp
public class SVGMaskElementBuilder : SVGElementBuilder<SVGMaskElement>, ICompositeElementBuilder, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IRectAttributeSetter
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SVGMaskElementBuilder](svgmaskelementbuilder/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMaskElement](../../aspose.svg/svgmaskelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MaskContentUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskcontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Mengatur atribut 'maskContentUnits' pada elemen 'mask' SVG, yang menentukan sistem koordinat untuk isi mask. |
| [MaskUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskunits/)(*[CoordinateUnits](../coordinateunits/)*) | Mengatur atribut 'maskUnits' pada elemen 'mask' SVG, yang menentukan sistem koordinat untuk atribut mask. |

### Lihat Juga

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMaskElement](../../aspose.svg/svgmaskelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
