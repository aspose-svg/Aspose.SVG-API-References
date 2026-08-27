---
title: "SVGBuilderExtensions.AddRect"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddRect. Menambahkan konfigurasi elemen rect ke builder."
type: docs
weight: 450
url: /id/net/aspose.svg.builder/svgbuilderextensions/addrect/
---
## AddRect<TBuilder>(*this TBuilder, Action&lt;SVGRectElementBuilder&gt;*) {#addrect_1}

Menambahkan konfigurasi elemen 'rect' ke builder.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    Action<SVGRectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'rect'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRect<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGRectElementBuilder&gt;*) {#addrect}

Menambahkan elemen 'rect' (persegi panjang) dengan dimensi dan gaya yang ditentukan ke builder SVG.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGRectElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi builder SVG yang akan ditambahkan elemen 'rect'. |
| x | Koordinat x titik awal persegi panjang. Dapat berupa nilai double atau tuple dari double dan LengthType. |
| y | Koordinat y titik awal persegi panjang. Dapat berupa nilai double atau tuple dari double dan LengthType. |
| width | Lebar persegi panjang. Dapat berupa nilai double atau tuple double dan LengthType. |
| height | Tinggi persegi panjang. Dapat berupa nilai double atau tuple double dan LengthType. |
| fill | Warna isi atau gaya cat untuk persegi panjang. Dapat berupa Color atau nilai enum Paint atau ID server cat. Parameter opsional. |
| stroke | Warna garis tepi atau gaya cat untuk outline persegi panjang. Dapat berupa Color atau nilai enum Paint atau ID server cat. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen persegi panjang. Parameter opsional. |
| extend | Aksi opsional untuk lebih mengonfigurasi pembuat elemen persegi panjang. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
