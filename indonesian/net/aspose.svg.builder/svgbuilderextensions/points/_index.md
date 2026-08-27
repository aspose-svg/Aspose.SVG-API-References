---
title: "SVGBuilderExtensions.Points"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions Points. Menetapkan atribut points untuk elemen SVG menggunakan array double."
type: docs
weight: 1910
url: /id/net/aspose.svg.builder/svgbuilderextensions/points/
---
## Points<TBuilder>(*this TBuilder, params double[]*) {#points}

Mengatur atribut 'points' untuk elemen SVG menggunakan array bilangan ganda.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params double[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| titik | Array double yang mewakili titik-titik (harus berjumlah genap). |

### Nilai Kembalian

Instansi builder untuk chaining.

### Pengecualian

| exception | kondisi |
| --- | --- |
| ArgumentException | Dilemparkan jika jumlah titik yang diberikan ganjil. |

### Lihat Juga

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Points<TBuilder>(*this TBuilder, params PointF[]*) {#points_1}

Mengatur atribut 'points' untuk elemen SVG menggunakan array objek PointF.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params PointF[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| titik | Array objek PointF yang mewakili titik-titik. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
