---
title: "SVGBuilderExtensions.AddFeDisplacementMap"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "SVGBuilderExtensions AddFeDisplacementMap method. Menambahkan konfigurasi elemen feDisplacementMap ke builder. Elemen ini memindahkan gambar dengan peta vektor yang ditentukan"
type: docs
weight: 190
url: /id/net/aspose.svg.builder/svgbuilderextensions/addfedisplacementmap/
---
## AddFeDisplacementMap<TBuilder>(*this TBuilder, Action&lt;SVGFEDisplacementMapElementBuilder&gt;*) {#addfedisplacementmap}

Menambahkan konfigurasi elemen 'feDisplacementMap' ke pembuat. Elemen ini memindahkan sebuah gambar dengan peta vektor yang ditentukan.

```csharp
public static TBuilder AddFeDisplacementMap<TBuilder>(this TBuilder builder, 
    Action<SVGFEDisplacementMapElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'feDisplacementMap'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGFEDisplacementMapElementBuilder](../../svgfedisplacementmapelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDisplacementMap<TBuilder>(*this TBuilder, double?, ChannelSelector?, ChannelSelector?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDisplacementMapElementBuilder&gt;*) {#addfedisplacementmap_1}

Menambahkan elemen 'feDisplacementMap' ke pembuat SVG, menciptakan efek yang mendistorsi gambar berdasarkan data warna dari sumber kedua.

```csharp
public static TBuilder AddFeDisplacementMap<TBuilder>(this TBuilder builder, double? scale = null, 
    ChannelSelector? xChannelSelector = default, ChannelSelector? yChannelSelector = default, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDisplacementMapElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi builder SVG yang akan ditambahkan elemen 'feDisplacementMap'. |
| skala | Faktor skala yang menentukan besarnya perpindahan. Parameter opsional. |
| xChannelSelector | Saluran gambar in2 yang digunakan untuk perpindahan sepanjang sumbu x. Parameter opsional. |
| yChannelSelector | Saluran gambar in2 yang digunakan untuk perpindahan sepanjang sumbu y. Parameter opsional. |
| in | Gambar input yang akan dipindahkan. Bisa berupa string atau FilterInput. Parameter opsional. |
| in2 | Gambar yang menyediakan data perpindahan. Bisa berupa string atau FilterInput. Parameter opsional. |
| result | Pengidentifikasi hasil untuk filter primitif ini. Parameter opsional. |
| x | Koordinat x dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| y | Koordinat y dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| width | Lebar dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| height | Tinggi dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| fill | Warna isi, cat, atau ID server cat untuk elemen. Parameter opsional. |
| stroke | Warna garis, cat, atau ID server cat untuk elemen. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen primitif filter. Parameter opsional. |
| extend | Tindakan opsional untuk mengkonfigurasi lebih lanjut SVGFEDisplacementMapElementBuilder. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* enum [ChannelSelector](../../channelselector/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDisplacementMapElementBuilder](../../svgfedisplacementmapelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
