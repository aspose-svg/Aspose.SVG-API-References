---
title: "SVGGeometryElement.Combine"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode Combine SVGGeometryElement. Menggabungkan geometri ini dengan geometri SVG lain menggunakan operasi boolean dan mengembalikan elemen jalur baru yang berisi hasilnya."
type: docs
weight: 20
url: /id/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

Menggabungkan geometri ini dengan geometri SVG lain menggunakan operasi boolean, dan mengembalikan elemen `<path>` baru yang berisi hasilnya.

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | Geometri lain yang akan digabungkan. Harus berada dalam dokumen yang sama. |
| op | BooleanPathOp | Operator boolean yang diterapkan: Union (A UNION B), Difference (A - B), Intersection (A INTERSECT B), atau Exclusion (XOR). |

### Nilai Kembalian

[`SVGPathElement`](../../svgpathelement/) baru yang atribut `d`-nya mengkodekan hasil di ruang pengguna root `<svg>` (px CSS). Elemen ini tidak ditambahkan ke DOM.

### Pengecualian

| exception | kondisi |
| --- | --- |
| ArgumentNullException | Dikeluarkan jika *geometryElement* bernilai null. |
| InvalidOperationException | Dilemparkan jika elemen ini tidak memiliki dokumen pemilik. |
| NotSupportedException | Dilemparkan ketika operasi jalur boolean tidak tersedia; fitur ini memerlukan backend SkiaSharp (pasang paket Aspose.SVG.Drawing.SkiaSharp). |

### Lihat Juga

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
