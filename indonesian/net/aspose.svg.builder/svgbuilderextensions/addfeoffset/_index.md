---
title: "SVGBuilderExtensions.AddFeOffset"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddFeOffset. Menambahkan konfigurasi elemen feOffset ke builder. Elemen ini menggeser gambar masukan dengan vektor tertentu"
type: docs
weight: 260
url: /id/net/aspose.svg.builder/svgbuilderextensions/addfeoffset/
---
## AddFeOffset<TBuilder>(*this TBuilder, Action&lt;SVGFEOffsetElementBuilder&gt;*) {#addfeoffset}

Menambahkan konfigurasi elemen 'feOffset' ke pembuat. Elemen ini menggeser gambar input dengan vektor yang ditentukan.

```csharp
public static TBuilder AddFeOffset<TBuilder>(this TBuilder builder, 
    Action<SVGFEOffsetElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'feOffset'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGFEOffsetElementBuilder](../../svgfeoffsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeOffset<TBuilder>(*this TBuilder, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEOffsetElementBuilder&gt;*) {#addfeoffset_1}

Menambahkan elemen 'feOffset' ke pembuat SVG, menciptakan efek offset dengan menggeser gambar input menggunakan vektor yang ditentukan.

```csharp
public static TBuilder AddFeOffset<TBuilder>(this TBuilder builder, double? dx = null, 
    double? dy = null, OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEOffsetElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi builder SVG yang akan ditambahkan elemen 'feOffset'. |
| dx | Jarak offset horizontal. Parameter opsional. |
| dy | Jarak offset vertikal. Parameter opsional. |
| in | Gambar input yang akan diterapkan offset. Dapat berupa string atau FilterInput. Parameter opsional. |
| result | Pengidentifikasi hasil untuk filter primitif ini. Parameter opsional. |
| x | Koordinat x dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| y | Koordinat y dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| width | Lebar dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| height | Tinggi dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| fill | Warna isi, cat, atau ID server cat untuk elemen. Parameter opsional. |
| stroke | Warna garis, cat, atau ID server cat untuk elemen. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen primitif filter. Parameter opsional. |
| extend | Aksi opsional untuk lebih mengkonfigurasi SVGFEOffsetElementBuilder. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEOffsetElementBuilder](../../svgfeoffsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
