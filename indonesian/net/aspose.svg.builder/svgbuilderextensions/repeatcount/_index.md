---
title: "SVGBuilderExtensions.RepeatCount"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode RepeatCount SVGBuilderExtensions. Mengatur atribut repeatCount yang menentukan berapa kali animasi harus diulang"
type: docs
weight: 1950
url: /id/net/aspose.svg.builder/svgbuilderextensions/repeatcount/
---
## RepeatCount<TBuilder>(*this TBuilder, int*) {#repeatcount_1}

Mengatur atribut 'repeatCount', mendefinisikan berapa kali animasi harus diulang.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, int value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| nilai | Jumlah kali animasi harus diulang. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatCount<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatcount}

Mengatur atribut 'repeatCount', mendefinisikan jumlah pengulangan tak terbatas untuk animasi menggunakan enum yang telah ditentukan.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| nilai | Jumlah pengulangan tak terbatas yang telah ditentukan sebelumnya untuk animasi. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
