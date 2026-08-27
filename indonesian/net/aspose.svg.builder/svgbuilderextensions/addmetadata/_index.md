---
title: "SVGBuilderExtensions.AddMetadata"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddMetadata. Menambahkan konfigurasi elemen metadata ke builder. Elemen metadata digunakan untuk menambahkan metadata ke konten SVG."
type: docs
weight: 390
url: /id/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

Menambahkan konfigurasi elemen 'metadata' ke pembuat. Elemen 'metadata' digunakan untuk menambahkan metadata ke konten SVG.

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| TElement | Tipe yang mewakili elemen 'metadata' dalam model SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'metadata'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
