---
title: "SVGBuilderExtensions.AddContent"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode AddContent SVGBuilderExtensions. Menambahkan konten teks ke elemen SVG."
type: docs
weight: 90
url: /id/net/aspose.svg.builder/svgbuilderextensions/addcontent/
---
## SVGBuilderExtensions.AddContent<TBuilder> method

Menambahkan konten teks ke elemen SVG.

```csharp
public static TBuilder AddContent<TBuilder>(this TBuilder builder, string text)
    where TBuilder : ISVGElementBuilder, ITextContentSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| teks | Teks yang akan ditambahkan ke elemen. |

### Nilai Kembalian

Instansi builder untuk chaining.

## Catatan

Metode ini memungkinkan penambahan konten teks secara langsung ke elemen SVG. Ini berguna untuk elemen yang berisi data teks.

### Lihat Juga

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentSetter](../../itextcontentsetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
