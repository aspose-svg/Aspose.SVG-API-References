---
title: "SVGBuilderExtensions.AddFeTurbulence"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddFeTurbulence. Menambahkan konfigurasi elemen feTurbulence ke builder. Elemen ini membuat gambar menggunakan noise Perlin yang berguna untuk membuat tekstur seperti awan atau marmer."
type: docs
weight: 290
url: /id/net/aspose.svg.builder/svgbuilderextensions/addfeturbulence/
---
## AddFeTurbulence<TBuilder>(*this TBuilder, Action&lt;SVGFETurbulenceElementBuilder&gt;*) {#addfeturbulence_1}

Menambahkan konfigurasi elemen 'feTurbulence' ke pembuat. Elemen ini membuat gambar menggunakan noise Perlin, berguna untuk membuat tekstur seperti awan atau marmer.

```csharp
public static TBuilder AddFeTurbulence<TBuilder>(this TBuilder builder, 
    Action<SVGFETurbulenceElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'feTurbulence'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGFETurbulenceElementBuilder](../../svgfeturbulenceelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeTurbulence<TBuilder>(*this TBuilder, OneOf&lt;double, (double, double)&gt;, int?, double?, StitchTiles?, TurbulenceType?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFETurbulenceElementBuilder&gt;*) {#addfeturbulence}

Menambahkan elemen 'feTurbulence' ke pembuat SVG, membuat efek turbulensi, seperti awan atau marmer, menggunakan noise Perlin.

```csharp
public static TBuilder AddFeTurbulence<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, double)> baseFrequency = null, int? numOctaves = null, 
    double? seed = null, StitchTiles? stitchTiles = default, TurbulenceType? type = default, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFETurbulenceElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi builder SVG yang akan ditambahkan elemen 'feTurbulence'. |
| baseFrequency | Frekuensi dasar dari turbulensi. Dapat berupa double atau ValueTuple dari dua double. Parameter opsional. |
| numOctaves | Jumlah oktaf untuk turbulensi. Parameter opsional. |
| seed | Nomor seed untuk generator angka acak. Parameter opsional. |
| stitchTiles | Menunjukkan apakah ubin disatukan. Parameter opsional. |
| type | Jenis turbulensi (noise fraktal atau turbulensi). Parameter opsional. |
| in | Gambar input yang akan diterapkan efek turbulensi. Dapat berupa string atau FilterInput. Parameter opsional. |
| result | Pengidentifikasi hasil untuk filter primitif ini. Parameter opsional. |
| x | Koordinat x dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| y | Koordinat y dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| width | Lebar dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| height | Tinggi dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| fill | Warna isi, cat, atau ID server cat untuk elemen. Parameter opsional. |
| stroke | Warna garis, cat, atau ID server cat untuk elemen. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen primitif filter. Parameter opsional. |
| extend | Aksi opsional untuk lebih lanjut mengkonfigurasi SVGFETurbulenceElementBuilder. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [StitchTiles](../../stitchtiles/)
* enum [TurbulenceType](../../turbulencetype/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFETurbulenceElementBuilder](../../svgfeturbulenceelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
