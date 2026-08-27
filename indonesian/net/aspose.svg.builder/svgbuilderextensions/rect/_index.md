---
title: "SVGBuilderExtensions.Rect"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions Rect. Mengatur atribut x y width dan height untuk elemen SVG guna mendefinisikan sebuah persegi panjang"
type: docs
weight: 1920
url: /id/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

Mengatur atribut 'x', 'y', 'width', dan 'height' untuk elemen SVG untuk mendefinisikan sebuah persegi panjang.

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| x | Koordinat x persegi panjang. |
| y | Koordinat y persegi panjang. |
| width | Lebar persegi panjang. |
| height | Tinggi persegi panjang. |
| type | Jenis pengukuran panjang untuk semua dimensi (default adalah piksel). |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
