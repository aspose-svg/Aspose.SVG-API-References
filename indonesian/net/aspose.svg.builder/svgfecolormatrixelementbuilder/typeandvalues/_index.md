---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode TypeAndValues SVGFEColorMatrixElementBuilder. Menetapkan atribut type dan values pada elemen feColorMatrix yang menentukan operasi matriks warna dan parameternya"
type: docs
weight: 30
url: /id/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

Mengatur atribut 'type' dan 'values' pada elemen feColorMatrix, menentukan operasi matriks warna dan parameternya.

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | ColorMatrixOperation | Nilai enum ColorMatrixOperation yang mewakili tipe operasi matriks warna. |
| nilai | Double[] | Parameter untuk operasi matriks warna. |

### Nilai Kembalian

Instance builder saat ini.

### Pengecualian

| exception | kondisi |
| --- | --- |
| ArgumentException | Dilemparkan ketika nilai yang diberikan tidak sesuai dengan persyaratan tipe yang ditentukan. |
| NotSupportedException | Dilemparkan ketika tipe operasi matriks yang tidak didukung diberikan. |

### Lihat Juga

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
