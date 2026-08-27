---
title: "SVGBuilderExtensions.TextLength"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions TextLength. Mengatur panjang tepat dari konten teks"
type: docs
weight: 2220
url: /id/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

Mengatur panjang tepat dari konten teks.

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| nilai | Panjang teks. |
| type | Jenis satuan panjang untuk nilai tersebut. |

### Nilai Kembalian

Instansi builder untuk chaining.

## Catatan

Metode ini mengatur atribut 'textLength', menentukan panjang yang diinginkan dari konten teks, yang berpotensi menggantikan panjang teks alami.

### Lihat Juga

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
