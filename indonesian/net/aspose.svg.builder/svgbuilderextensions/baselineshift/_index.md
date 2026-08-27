---
title: "SVGBuilderExtensions.BaselineShift"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode BaselineShift SVGBuilderExtensions. Mengatur atribut baseline-shift untuk elemen SVG menggunakan nilai yang telah ditentukan"
type: docs
weight: 600
url: /id/net/aspose.svg.builder/svgbuilderextensions/baselineshift/
---
## BaselineShift<TBuilder>(*this TBuilder, [BaseLineShift](../../baselineshift/)*) {#baselineshift}

Mengatur atribut 'baseline-shift' untuk elemen SVG menggunakan nilai yang telah ditentukan.

```csharp
public static TBuilder BaselineShift<TBuilder>(this TBuilder builder, BaseLineShift value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| nilai | Nilai pergeseran baseline yang akan diatur. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* enum [BaseLineShift](../../baselineshift/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## BaselineShift<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#baselineshift_1}

Mengatur atribut 'baseline-shift' untuk elemen SVG menggunakan nilai numerik.

```csharp
public static TBuilder BaselineShift<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| nilai | Nilai numerik untuk pergeseran baseline. |
| type | Jenis satuan panjang. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
