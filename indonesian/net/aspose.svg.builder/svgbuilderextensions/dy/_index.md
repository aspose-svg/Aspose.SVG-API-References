---
title: "SVGBuilderExtensions.Dy"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions Dy. Menetapkan beberapa nilai penyesuaian vertikal untuk konten teks."
type: docs
weight: 780
url: /id/net/aspose.svg.builder/svgbuilderextensions/dy/
---
## Dy<TBuilder>(*this TBuilder, double[], [LengthType](../../lengthtype/)*) {#dy_1}

Mengatur beberapa nilai penyesuaian vertikal untuk konten teks.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double[] values, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| nilai | Array nilai penyesuaian vertikal. |
| type | Jenis satuan panjang untuk nilai-nilai tersebut. |

### Nilai Kembalian

Instansi builder untuk chaining.

## Catatan

Metode ini menetapkan atribut 'dy' dengan beberapa nilai, memungkinkan penyesuaian vertikal individual untuk setiap karakter atau segmen teks.

### Lihat Juga

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dy<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dy}

Mengatur nilai penyesuaian vertikal tunggal untuk konten teks.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| nilai | Nilai penyesuaian vertikal. |
| type | Jenis satuan panjang untuk nilai tersebut. |

### Nilai Kembalian

Instansi builder untuk chaining.

## Catatan

Metode ini menetapkan atribut 'dy' dengan satu nilai, menyesuaikan posisi vertikal konten teks.

### Lihat Juga

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
