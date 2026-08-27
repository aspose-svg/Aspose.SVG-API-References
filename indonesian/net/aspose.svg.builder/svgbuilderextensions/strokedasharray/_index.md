---
title: "SVGBuilderExtensions.StrokeDashArray"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode StrokeDashArray SVGBuilderExtensions. Mengatur atribut stroke-dasharray untuk elemen SVG yang mendefinisikan pola garis putus-putus dan celah yang digunakan untuk melukis garis."
type: docs
weight: 2090
url: /id/net/aspose.svg.builder/svgbuilderextensions/strokedasharray/
---
## StrokeDashArray<TBuilder>(*this TBuilder, params double[]*) {#strokedasharray_1}

Mengatur atribut 'stroke-dasharray' untuk elemen SVG, menentukan pola dash dan celah yang digunakan untuk melukis stroke.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, params double[] dashArray)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| dashArray | Array panjang dash. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StrokeDashArray<TBuilder>(*this TBuilder, [Dash](../../dash/)*) {#strokedasharray}

Mengatur atribut 'stroke-dasharray' untuk elemen SVG menggunakan pola dash yang telah ditentukan.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, Dash value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| nilai | Pola dash yang akan diatur. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* enum [Dash](../../dash/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
