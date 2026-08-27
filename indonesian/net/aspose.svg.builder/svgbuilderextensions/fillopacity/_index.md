---
title: "SVGBuilderExtensions.FillOpacity"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions FillOpacity. Menetapkan atribut fill-opacity untuk elemen SVG. Nilai harus antara 0.0 transparan penuh dan 1.0 opak penuh"
type: docs
weight: 820
url: /id/net/aspose.svg.builder/svgbuilderextensions/fillopacity/
---
## SVGBuilderExtensions.FillOpacity<TBuilder> method

Mengatur atribut 'fill-opacity' untuk elemen SVG. Nilai harus antara 0.0 (sepenuhnya transparan) dan 1.0 (sepenuhnya opak).

```csharp
public static TBuilder FillOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| opacity | Nilai opacity yang akan diatur. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Pengecualian

| exception | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | Dilemparkan jika opacity tidak berada dalam rentang yang valid. |

### Lihat Juga

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
