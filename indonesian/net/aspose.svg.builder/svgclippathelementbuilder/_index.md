---
title: "SVGClipPathElementBuilder Kelas"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Aspose.Svg.Builder.SVGClipPathElementBuilder class. Kelas builder untuk membangun elemen SVG clipPath yang digunakan untuk mendefinisikan jalur pemotongan. Ini memungkinkan pembuatan konten di dalam elemen clipPath dan menyediakan metode untuk mengatur berbagai atribut khusus elemen clipPath dalam SVG."
type: docs
weight: 1130
url: /id/net/aspose.svg.builder/svgclippathelementbuilder/
---
## SVGClipPathElementBuilder class

Kelas builder untuk membangun elemen SVG 'clipPath', yang digunakan untuk mendefinisikan jalur pemotongan. Ini memungkinkan pembuatan konten di dalam elemen 'clipPath' dan menyediakan metode untuk mengatur berbagai atribut khusus elemen 'clipPath' dalam SVG.

```csharp
public class SVGClipPathElementBuilder : SVGElementBuilder<SVGClipPathElement>, 
    IAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IShapeElementBuilder
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SVGClipPathElementBuilder](svgclippathelementbuilder/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgclippathelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Menambahkan elemen script ke elemen clipPath. |
| [AddText](../../aspose.svg.builder/svgclippathelementbuilder/addtext/)(*Action&lt;SVGTextElementBuilder&gt;*) | Menambahkan elemen teks ke elemen clipPath. |
| [AddUse](../../aspose.svg.builder/svgclippathelementbuilder/adduse/)(*Action&lt;SVGUseElementBuilder&gt;*) | Menambahkan elemen 'use' ke elemen clipPath. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGClipPathElement](../../aspose.svg/svgclippathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ClipPathUnits](../../aspose.svg.builder/svgclippathelementbuilder/clippathunits/)(*[CoordinateUnits](../coordinateunits/)*) | Mengatur atribut 'clipPathUnits' pada elemen SVG 'clipPath', yang menentukan sistem koordinat untuk jalur pemotongan. |

### Lihat Juga

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGClipPathElement](../../aspose.svg/svgclippathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IShapeElementBuilder](../ishapeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
