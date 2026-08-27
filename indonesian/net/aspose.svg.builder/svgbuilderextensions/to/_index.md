---
title: "SVGBuilderExtensions.To"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions To. Menetapkan atribut to yang mendefinisikan nilai akhir animasi dengan tipe panjang yang ditentukan."
type: docs
weight: 2250
url: /id/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

Mengatur atribut 'to', mendefinisikan nilai akhir animasi dengan tipe panjang yang ditentukan.

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| nilai | Nilai akhir untuk animasi. |
| type | Tipe panjang untuk nilai 'to'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
