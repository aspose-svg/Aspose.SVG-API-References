---
title: "SVGBuilderExtensions.AddFeMerge"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddFeMerge. Menambahkan konfigurasi elemen feMerge ke builder. Elemen ini memungkinkan efek filter diterapkan secara bersamaan bukan secara berurutan."
type: docs
weight: 240
url: /id/net/aspose.svg.builder/svgbuilderextensions/addfemerge/
---
## SVGBuilderExtensions.AddFeMerge<TBuilder> method

Menambahkan konfigurasi elemen 'feMerge' ke pembuat. Elemen ini memungkinkan efek filter diterapkan secara bersamaan, bukan secara berurutan.

```csharp
public static TBuilder AddFeMerge<TBuilder>(this TBuilder builder, 
    Action<SVGFEMergeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'feMerge'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGFEMergeElementBuilder](../../svgfemergeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
