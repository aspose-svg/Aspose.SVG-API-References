---
title: "SVGBuilderExtensions.AddFeBlend"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode AddFeBlend SVGBuilderExtensions. Menambahkan konfigurasi elemen feBlend ke builder. Elemen ini mendefinisikan efek perpaduan antara dua grafik."
type: docs
weight: 130
url: /id/net/aspose.svg.builder/svgbuilderextensions/addfeblend/
---
## AddFeBlend<TBuilder>(*this TBuilder, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend}

Menambahkan konfigurasi elemen 'feBlend' ke builder. Elemen ini mendefinisikan efek perpaduan antara dua grafik.

```csharp
public static TBuilder AddFeBlend<TBuilder>(this TBuilder builder, 
    Action<SVGFEBlendElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'feBlend'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGFEBlendElementBuilder](../../svgfeblendelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeBlend<TBuilder>(*this TBuilder, BlendMode?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend_1}

Menambahkan elemen 'feBlend' ke builder SVG, menentukan mode perpaduan dan berbagai properti lainnya untuk efek filter.

```csharp
public static TBuilder AddFeBlend<TBuilder>(this TBuilder builder, BlendMode? mode = default, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEBlendElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi builder SVG tempat elemen 'feBlend' akan ditambahkan. |
| mode | Mode perpaduan yang akan digunakan. Parameter opsional. |
| in | Input pertama untuk efek perpaduan. Dapat berupa string atau FilterInput. Parameter opsional. |
| in2 | Input kedua untuk efek perpaduan. Dapat berupa string atau FilterInput. Parameter opsional. |
| result | Pengidentifikasi hasil untuk filter primitif ini. Parameter opsional. |
| x | Koordinat x dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| y | Koordinat y dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| width | Lebar dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| height | Tinggi dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| fill | Warna isi, cat, atau ID server cat untuk elemen. Parameter opsional. |
| stroke | Warna garis, cat, atau ID server cat untuk elemen. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen primitif filter. Parameter opsional. |
| extend | Aksi opsional untuk lebih lanjut mengkonfigurasi SVGFEBlendElementBuilder. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* enum [BlendMode](../../blendmode/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEBlendElementBuilder](../../svgfeblendelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
