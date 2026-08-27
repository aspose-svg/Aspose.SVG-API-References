---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions TextDecoration. Menetapkan atribut text-decoration untuk elemen SVG yang mendefinisikan dekorasi yang ditambahkan ke teks."
type: docs
weight: 2210
url: /id/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

Mengatur atribut 'text-decoration' untuk elemen SVG, mendefinisikan dekorasi yang ditambahkan pada teks.

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| underline | Menentukan apakah teks harus digarisbawahi. |
| overline | Menentukan apakah teks harus memiliki garis atas. |
| lineThrough | Menentukan apakah teks harus memiliki garis coret. |
| blink | Menentukan apakah teks harus berkedip (tidak disarankan untuk digunakan). |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
