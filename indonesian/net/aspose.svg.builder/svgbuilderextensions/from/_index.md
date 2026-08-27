---
title: "SVGBuilderExtensions.From"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions From. Menetapkan atribut from yang mendefinisikan nilai awal animasi dengan tipe panjang yang ditentukan."
type: docs
weight: 960
url: /id/net/aspose.svg.builder/svgbuilderextensions/from/
---
## SVGBuilderExtensions.From<TBuilder> method

Mengatur atribut 'from', mendefinisikan nilai awal animasi dengan tipe panjang yang ditentukan.

```csharp
public static TBuilder From<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| nilai | Nilai awal untuk animasi. |
| type | Tipe panjang untuk nilai 'from'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
