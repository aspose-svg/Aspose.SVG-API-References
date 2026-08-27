---
title: "SVGBuilderExtensions.AddDesc"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddDesc. Menambahkan konfigurasi elemen desc ke builder. Elemen desc digunakan untuk memberikan deskripsi bagi konten SVG."
type: docs
weight: 110
url: /id/net/aspose.svg.builder/svgbuilderextensions/adddesc/
---
## SVGBuilderExtensions.AddDesc<TBuilder> method

Menambahkan konfigurasi elemen 'desc' ke builder. Elemen 'desc' digunakan untuk memberikan deskripsi bagi konten SVG.

```csharp
public static TBuilder AddDesc<TBuilder>(this TBuilder builder, 
    Action<SVGDescElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'desc'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGDescElementBuilder](../../svgdescelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
