---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddBuilder. Menambahkan pembuat elemen SVG yang ada ke pembuat elemen SVG saat ini. Metode ini digunakan untuk menyertakan pembuat elemen SVG yang telah ditentukan ke dalam pembuat saat ini."
type: docs
weight: 60
url: /id/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

Menambahkan builder elemen SVG yang ada ke builder elemen SVG saat ini. Metode ini digunakan untuk menyertakan builder elemen SVG yang telah ditentukan sebelumnya ke dalam builder saat ini.

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| TElementBuilder | Tipe pembuat elemen SVG yang akan dikonfigurasi. TElementBuilder harus mengimplementasikan ISVGElementBuilder. |
| builder | Pembuat elemen SVG ke mana pembuat elemen lain ditambahkan. |
| elementBuilder | Pembuat elemen SVG yang akan ditambahkan. |

### Nilai Kembalian

Builder elemen SVG asli untuk chaining metode.

### Lihat Juga

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
