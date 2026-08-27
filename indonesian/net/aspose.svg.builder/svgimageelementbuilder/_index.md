---
title: "Kelas SVGImageElementBuilder"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Kelas Aspose.Svg.Builder.SVGImageElementBuilder. Kelas pembangun untuk membuat elemen gambar SVG. Elemen ini digunakan untuk menyematkan gambar dalam grafik SVG. Ini menyediakan metode untuk mengatur berbagai atribut khusus elemen gambar dan menambahkan konfigurasi tambahan seperti jalur klip, masker, gaya, dan skrip."
type: docs
weight: 1470
url: /id/net/aspose.svg.builder/svgimageelementbuilder/
---
## SVGImageElementBuilder class

Kelas Builder untuk membangun elemen SVG 'image'. Elemen ini digunakan untuk menyematkan gambar dalam grafik SVG. Ia menyediakan metode untuk mengatur berbagai atribut khusus elemen 'image' dan menambahkan konfigurasi tambahan seperti jalur klip, masker, gaya, dan skrip.

```csharp
public class SVGImageElementBuilder : SVGElementBuilder<SVGImageElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SVGImageElementBuilder](svgimageelementbuilder/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddClipPath](../../aspose.svg.builder/svgimageelementbuilder/addclippath/)(*Action&lt;SVGClipPathElementBuilder&gt;*) | Menambahkan konfigurasi jalur klip ke elemen SVG 'image'. |
| [AddMask](../../aspose.svg.builder/svgimageelementbuilder/addmask/)(*Action&lt;SVGMaskElementBuilder&gt;*) | Menambahkan konfigurasi masker ke elemen SVG 'image'. |
| [AddScript](../../aspose.svg.builder/svgimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Menambahkan konfigurasi skrip ke elemen SVG 'image'. |
| [AddStyle](../../aspose.svg.builder/svgimageelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Menambahkan konfigurasi gaya ke elemen SVG 'image'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGImageElement](../../aspose.svg/svgimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgimageelementbuilder/href/)(*string*) | Mengatur atribut 'href' pada elemen SVG 'image', menentukan URL gambar yang akan disematkan. |
| [HrefBase64FromBytes](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64frombytes/)(*byte[], string*) | Mengatur atribut 'href' pada elemen SVG 'image' menggunakan byte gambar yang dikodekan base64. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile)(*string*) | Mengatur atribut 'href' pada elemen SVG 'image' menggunakan file gambar yang dikodekan base64. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile_1)(*string, string*) | Mengatur atribut 'href' pada elemen SVG 'image' menggunakan file gambar yang dikodekan base64 dengan tipe MIME yang ditentukan. |

### Lihat Juga

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGImageElement](../../aspose.svg/svgimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
