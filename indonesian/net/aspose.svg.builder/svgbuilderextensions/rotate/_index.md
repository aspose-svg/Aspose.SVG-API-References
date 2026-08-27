---
title: "SVGBuilderExtensions.Rotate"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions Rotate. Menetapkan sudut rotasi untuk karakter individual atau segmen konten teks."
type: docs
weight: 2000
url: /id/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

Mengatur sudut rotasi untuk masing-masing karakter atau segmen konten teks.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| nilai | Array sudut rotasi dalam derajat. |

### Nilai Kembalian

Instansi builder untuk chaining.

## Catatan

Metode ini mengatur atribut 'rotate' dengan beberapa nilai, memungkinkan rotasi individual untuk setiap karakter atau segmen teks.

### Lihat Juga

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

Mengatur satu sudut rotasi untuk seluruh konten teks.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| nilai | Sudut rotasi dalam derajat. |

### Nilai Kembalian

Instansi builder untuk chaining.

## Catatan

Metode ini mengatur atribut 'rotate' dengan satu nilai, menerapkan sudut rotasi yang sama pada semua konten teks.

### Lihat Juga

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
