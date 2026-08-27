---
title: "SVGBuilderExtensions.AddFeComponentTransfer"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddFeComponentTransfer. Menambahkan konfigurasi elemen feComponentTransfer ke builder. Elemen ini melakukan pemetaan ulang data per komponen untuk saluran warna."
type: docs
weight: 150
url: /id/net/aspose.svg.builder/svgbuilderextensions/addfecomponenttransfer/
---
## AddFeComponentTransfer<TBuilder>(*this TBuilder, Action&lt;SVGFEComponentTransferElementBuilder&gt;*) {#addfecomponenttransfer}

Menambahkan konfigurasi elemen 'feComponentTransfer' ke builder. Elemen ini melakukan pemetaan ulang komponen data untuk saluran warna.

```csharp
public static TBuilder AddFeComponentTransfer<TBuilder>(this TBuilder builder, 
    Action<SVGFEComponentTransferElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'feComponentTransfer'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGFEComponentTransferElementBuilder](../../svgfecomponenttransferelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeComponentTransfer<TBuilder>(*this TBuilder, Action&lt;SVGFEFuncAElementBuilder&gt;, Action&lt;SVGFEFuncRElementBuilder&gt;, Action&lt;SVGFEFuncGElementBuilder&gt;, Action&lt;SVGFEFuncBElementBuilder&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEComponentTransferElementBuilder&gt;*) {#addfecomponenttransfer_1}

Menambahkan elemen 'feComponentTransfer' ke builder SVG, memungkinkan pemetaan ulang komponen data untuk saluran warna.

```csharp
public static TBuilder AddFeComponentTransfer<TBuilder>(this TBuilder builder, 
    Action<SVGFEFuncAElementBuilder> a = null, Action<SVGFEFuncRElementBuilder> r = null, 
    Action<SVGFEFuncGElementBuilder> g = null, Action<SVGFEFuncBElementBuilder> b = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEComponentTransferElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi builder SVG yang akan ditambahkan elemen 'feComponentTransfer'. |
| a | Aksi untuk mengonfigurasi komponen 'feFuncA' untuk saluran alfa. Parameter opsional. |
| r | Aksi untuk mengonfigurasi komponen 'feFuncR' untuk saluran merah. Parameter opsional. |
| g | Aksi untuk mengonfigurasi komponen 'feFuncG' untuk saluran hijau. Parameter opsional. |
| b | Aksi untuk mengonfigurasi komponen 'feFuncB' untuk saluran biru. Parameter opsional. |
| in | Input untuk efek transfer komponen. Dapat berupa string atau FilterInput. Parameter opsional. |
| result | Pengidentifikasi hasil untuk filter primitif ini. Parameter opsional. |
| x | Koordinat x dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| y | Koordinat y dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| width | Lebar dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| height | Tinggi dari subregion primitif filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| fill | Warna isi, cat, atau ID server cat untuk elemen. Parameter opsional. |
| stroke | Warna garis, cat, atau ID server cat untuk elemen. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen primitif filter. Parameter opsional. |
| extend | Aksi opsional untuk lebih lanjut mengonfigurasi SVGFEComponentTransferElementBuilder. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* class [SVGFEFuncAElementBuilder](../../svgfefuncaelementbuilder/)
* class [SVGFEFuncRElementBuilder](../../svgfefuncrelementbuilder/)
* class [SVGFEFuncGElementBuilder](../../svgfefuncgelementbuilder/)
* class [SVGFEFuncBElementBuilder](../../svgfefuncbelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEComponentTransferElementBuilder](../../svgfecomponenttransferelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
