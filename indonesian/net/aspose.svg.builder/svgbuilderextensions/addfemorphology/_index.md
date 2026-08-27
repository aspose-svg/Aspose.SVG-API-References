---
title: "SVGBuilderExtensions.AddFeMorphology"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddFeMorphology. Menambahkan konfigurasi elemen feMorphology ke builder. Elemen ini digunakan untuk menerapkan operasi morfologi seperti dilasi atau erosi pada gambar input."
type: docs
weight: 250
url: /id/net/aspose.svg.builder/svgbuilderextensions/addfemorphology/
---
## AddFeMorphology<TBuilder>(*this TBuilder, Action&lt;SVGFEMorphologyElementBuilder&gt;*) {#addfemorphology}

Menambahkan konfigurasi elemen 'feMorphology' ke pembuat. Elemen ini digunakan untuk menerapkan operasi morfologi seperti dilasi atau erosi pada gambar input.

```csharp
public static TBuilder AddFeMorphology<TBuilder>(this TBuilder builder, 
    Action<SVGFEMorphologyElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'feMorphology'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGFEMorphologyElementBuilder](../../svgfemorphologyelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeMorphology<TBuilder>(*this TBuilder, MorphologyOperator?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEMorphologyElementBuilder&gt;*) {#addfemorphology_1}

Menambahkan elemen 'feMorphology' ke pembuat SVG, menerapkan operasi morfologi pada gambar input.

```csharp
public static TBuilder AddFeMorphology<TBuilder>(this TBuilder builder, 
    MorphologyOperator? @operator = default, OneOf<double, (double, double)> radius = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEMorphologyElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi pembuat SVG ke mana elemen 'feMorphology' akan ditambahkan. |
| operator | Operator morfologi yang akan diterapkan. Parameter opsional. |
| radius | Radius untuk operasi morfologi. Dapat berupa double atau ValueTuple dari dua double. Parameter opsional. |
| in | Gambar input yang akan diterapkan operasi morfologi. Dapat berupa string atau FilterInput. Parameter opsional. |
| result | Pengidentifikasi hasil untuk filter primitif ini. Parameter opsional. |
| x | Koordinat x dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| y | Koordinat y dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| width | Lebar dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| height | Tinggi dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| fill | Warna isi, cat, atau ID server cat untuk elemen. Parameter opsional. |
| stroke | Warna garis, cat, atau ID server cat untuk elemen. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen primitif filter. Parameter opsional. |
| extend | Aksi opsional untuk lebih mengkonfigurasi SVGFEMorphologyElementBuilder. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* enum [MorphologyOperator](../../morphologyoperator/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEMorphologyElementBuilder](../../svgfemorphologyelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
