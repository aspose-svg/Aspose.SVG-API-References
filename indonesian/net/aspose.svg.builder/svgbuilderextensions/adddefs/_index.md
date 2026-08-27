---
title: "SVGBuilderExtensions.AddDefs"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode AddDefs SVGBuilderExtensions. Menambahkan konfigurasi elemen definisi defs ke builder."
type: docs
weight: 100
url: /id/net/aspose.svg.builder/svgbuilderextensions/adddefs/
---
## SVGBuilderExtensions.AddDefs<TBuilder> method

Menambahkan konfigurasi elemen 'defs' (definisi) ke builder.

```csharp
public static TBuilder AddDefs<TBuilder>(this TBuilder builder, 
    Action<SVGDefsElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'defs'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGDefsElementBuilder](../../svgdefselementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
