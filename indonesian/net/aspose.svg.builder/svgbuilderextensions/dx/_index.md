---
title: "SVGBuilderExtensions.Dx"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions Dx. Mengatur atribut dx untuk menyesuaikan posisi horizontal setiap karakter dalam teks"
type: docs
weight: 770
url: /id/net/aspose.svg.builder/svgbuilderextensions/dx/
---
## Dx<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#dx}

Mengatur atribut 'dx' untuk menyesuaikan posisi horizontal setiap karakter dalam teks.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| type | Jenis satuan panjang untuk nilai-nilai tersebut. |
| nilai | Nilai penyesuaian horizontal untuk setiap karakter. |

### Nilai Kembalian

Instansi builder untuk chaining.

## Catatan

Metode ini memungkinkan kontrol halus atas jarak horizontal karakter dalam teks.

### Lihat Juga

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dx<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dx_1}

Mengatur nilai penyesuaian horizontal tunggal untuk konten teks.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| nilai | Nilai penyesuaian horizontal. |
| type | Jenis satuan panjang untuk nilai tersebut. |

### Nilai Kembalian

Instansi builder untuk chaining.

## Catatan

Metode ini mengatur atribut 'dx' dengan satu nilai, menyesuaikan posisi horizontal konten teks.

### Lihat Juga

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
