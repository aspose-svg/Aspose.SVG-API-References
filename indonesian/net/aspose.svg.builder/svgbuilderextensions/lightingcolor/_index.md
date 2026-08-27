---
title: "SVGBuilderExtensions.LightingColor"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions LightingColor. Menetapkan atribut lighting-color untuk elemen SVG menggunakan nilai warna tertentu"
type: docs
weight: 1110
url: /id/net/aspose.svg.builder/svgbuilderextensions/lightingcolor/
---
## LightingColor<TBuilder>(*this TBuilder, Color*) {#lightingcolor_1}

Mengatur atribut 'lighting-color' untuk elemen SVG menggunakan nilai warna yang ditentukan.

```csharp
public static TBuilder LightingColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| colorValue | Nilai warna yang akan diatur untuk efek pencahayaan. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LightingColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#lightingcolor}

Mengatur atribut 'lighting-color' untuk elemen SVG menggunakan konfigurasi warna khusus.

```csharp
public static TBuilder LightingColor<TBuilder>(this TBuilder builder, 
    Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Delegasi untuk mengonfigurasi warna. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
