---
title: "Kelas SVGStopElementBuilder"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Kelas Aspose.Svg.Builder.SVGStopElementBuilder. Kelas pembangun untuk membuat elemen stop SVG. Elemen stop digunakan dalam definisi gradien, baik linear maupun radial, untuk mendefinisikan titik warna. Kelas ini menyediakan metode untuk mengatur berbagai atribut khusus elemen stop seperti offset dan warna."
type: docs
weight: 1620
url: /id/net/aspose.svg.builder/svgstopelementbuilder/
---
## SVGStopElementBuilder class

Kelas builder untuk membuat elemen SVG 'stop'. Elemen 'stop' digunakan dalam definisi gradien (baik linear maupun radial) untuk menentukan titik warna. Kelas ini menyediakan metode untuk mengatur berbagai atribut khusus elemen 'stop', seperti offset dan warna.

```csharp
public class SVGStopElementBuilder : SVGElementBuilder<SVGStopElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SVGStopElementBuilder](svgstopelementbuilder/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgstopelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Menambahkan konfigurasi skrip ke elemen SVG 'stop'. |
| [AddStyle](../../aspose.svg.builder/svgstopelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Menambahkan konfigurasi gaya ke elemen SVG 'stop'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStopElement](../../aspose.svg/svgstopelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Offset](../../aspose.svg.builder/svgstopelementbuilder/offset/)(*double, [StopUnitType](../stopunittype/)*) | Mengatur atribut 'offset' dari elemen SVG 'stop', yang menentukan posisi titik warna dalam gradien. |

### Lihat Juga

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStopElement](../../aspose.svg/svgstopelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
