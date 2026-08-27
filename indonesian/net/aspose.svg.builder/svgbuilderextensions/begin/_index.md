---
title: "SVGBuilderExtensions.Begin"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions Begin. Menetapkan atribut begin yang menentukan kapan animasi harus dimulai."
type: docs
weight: 610
url: /id/net/aspose.svg.builder/svgbuilderextensions/begin/
---
## SVGBuilderExtensions.Begin<TBuilder> method

Mengatur atribut 'begin', menentukan kapan animasi harus dimulai.

```csharp
public static TBuilder Begin<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| konfigurasi | Delegasi untuk mengonfigurasi nilai timing. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [TimingValueBuilder](../../timingvaluebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
