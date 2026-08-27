---
title: "Kelas SVGElementBuilderT"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Kelas Aspose.Svg.Builder.SVGElementBuilder1T. Mewakili kelas dasar untuk membangun elemen SVG tipe T."
type: docs
weight: 1160
url: /id/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

Mewakili kelas dasar untuk membangun elemen SVG tipe *T*.

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen SVG yang menjadi tanggung jawab builder ini untuk dibuat. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | Mendapatkan daftar konfigurasi yang akan diterapkan pada elemen SVG. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | Menambahkan konfigurasi atribut ke elemen SVG. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Membangun elemen SVG dan menerapkan semua konfigurasi padanya. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | Menerapkan konfigurasi pada elemen SVG yang sudah ada. |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | Membangun elemen SVG sebagai SVGElement generik. |

### Lihat Juga

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
