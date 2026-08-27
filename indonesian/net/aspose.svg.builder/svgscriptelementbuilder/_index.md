---
title: "Kelas SVGScriptElementBuilder"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Kelas Aspose.Svg.Builder.SVGScriptElementBuilder. Kelas pembangun untuk membuat elemen skrip SVG. Elemen skrip digunakan untuk menyematkan atau merujuk skrip yang dapat dieksekusi dalam dokumen SVG. Kelas ini menyediakan metode untuk mengatur berbagai atribut khusus elemen skrip seperti tipe, sumber, dan pengaturan cross-origin."
type: docs
weight: 1600
url: /id/net/aspose.svg.builder/svgscriptelementbuilder/
---
## SVGScriptElementBuilder class

Kelas builder untuk membuat elemen SVG 'script'. Elemen 'script' digunakan untuk menyematkan atau merujuk skrip yang dapat dieksekusi dalam dokumen SVG. Kelas ini menyediakan metode untuk mengatur berbagai atribut khusus elemen 'script', seperti tipe, sumber, dan pengaturan lintas asal.

```csharp
public class SVGScriptElementBuilder : SVGElementBuilder<SVGScriptElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SVGScriptElementBuilder](svgscriptelementbuilder/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGScriptElement](../../aspose.svg/svgscriptelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Crossorigin](../../aspose.svg.builder/svgscriptelementbuilder/crossorigin/)(*string*) | Menetapkan atribut 'crossorigin' pada elemen SVG 'script', menentukan pengaturan CORS untuk skrip eksternal. |
| [Href](../../aspose.svg.builder/svgscriptelementbuilder/href/)(*string*) | Menetapkan atribut 'href' pada elemen SVG 'script', menentukan URL berkas skrip eksternal. |
| [Type](../../aspose.svg.builder/svgscriptelementbuilder/type/)(*string*) | Menetapkan atribut 'type' pada elemen SVG 'script', menentukan jenis bahasa skrip (mis., "text/javascript"). |

### Lihat Juga

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGScriptElement](../../aspose.svg/svgscriptelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
