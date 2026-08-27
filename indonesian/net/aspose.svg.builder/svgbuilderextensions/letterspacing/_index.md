---
title: "SVGBuilderExtensions.LetterSpacing"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode LetterSpacing SVGBuilderExtensions. Menetapkan atribut letter-spacing untuk elemen SVG menggunakan nilai numerik dan tipe panjang tertentu."
type: docs
weight: 1100
url: /id/net/aspose.svg.builder/svgbuilderextensions/letterspacing/
---
## LetterSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#letterspacing_1}

Mengatur atribut 'letter-spacing' untuk elemen SVG menggunakan nilai numerik dan tipe panjang tertentu.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| nilai | Nilai letter-spacing yang akan ditetapkan. |
| type | Tipe panjang (mis., px, em). |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LetterSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#letterspacing}

Mengatur atribut 'letter-spacing' untuk elemen SVG menggunakan nilai spasi yang telah ditentukan.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| nilai | Nilai spasi yang telah ditentukan untuk ditetapkan. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
