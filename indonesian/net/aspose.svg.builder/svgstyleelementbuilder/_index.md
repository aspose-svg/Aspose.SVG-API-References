---
title: "Kelas SVGStyleElementBuilder"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Kelas Aspose.Svg.Builder.SVGStyleElementBuilder. Kelas pembangun untuk membuat elemen gaya SVG. Kelas ini memfasilitasi pembuatan dan konfigurasi elemen gaya SVG dengan aturan CSS."
type: docs
weight: 1630
url: /id/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

Kelas builder untuk membuat elemen SVG 'style'. Kelas ini memfasilitasi pembuatan dan konfigurasi elemen gaya SVG dengan aturan CSS.

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | Menambahkan komentar ke konten gaya. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | Menambahkan aturan CSS ke elemen gaya menggunakan RuleBuilder. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | Menambahkan aturan CSS ke elemen gaya. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Membangun elemen gaya SVG dengan aturan CSS yang terkumpul dan menambahkannya ke dokumen yang ditentukan. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | Mengatur atribut 'media' pada elemen 'style' SVG. Atribut ini menentukan media yang dituju oleh gaya, memungkinkan gaya bersifat kondisional berdasarkan tipe media. |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | Mengatur atribut 'title' pada elemen 'style' SVG. Atribut ini memberikan judul saran untuk elemen gaya, yang dapat berguna untuk aksesibilitas dan teks tooltip. |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | Mengatur atribut 'type' pada elemen 'style' SVG. Atribut ini menentukan bahasa lembar gaya dari isi elemen. |

### Lihat Juga

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
