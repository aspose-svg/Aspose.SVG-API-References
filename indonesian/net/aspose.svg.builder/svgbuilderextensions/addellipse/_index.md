---
title: "SVGBuilderExtensions.AddEllipse"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddEllipse. Menambahkan konfigurasi elemen elips ke builder."
type: docs
weight: 120
url: /id/net/aspose.svg.builder/svgbuilderextensions/addellipse/
---
## AddEllipse<TBuilder>(*this TBuilder, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse_1}

Menambahkan konfigurasi elemen 'ellipse' ke builder.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    Action<SVGEllipseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'ellipse'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddEllipse<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse}

Menambahkan elemen 'ellipse' ke builder SVG, menentukan pusat, radius, dan gaya.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> rx = null, OneOf<double, (double, LengthType)> ry = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGEllipseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi builder SVG yang akan ditambahkan elemen 'ellipse'. |
| cx | Koordinat x pusat elips. Dapat berupa nilai double atau tuple dari double dan LengthType. |
| cy | Koordinat y pusat elips. Dapat berupa nilai double atau tuple dari double dan LengthType. |
| rx | Radius x elips. Dapat berupa nilai double atau tuple dari double dan LengthType. |
| ry | Radius y elips. Dapat berupa nilai double atau tuple dari double dan LengthType. |
| fill | Warna isi atau gaya cat untuk elips. Dapat berupa Color atau nilai enum Paint atau ID server cat. Parameter opsional. |
| stroke | Warna garis atau gaya cat untuk elips. Dapat berupa Color atau nilai enum Paint atau ID server cat. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen elips. Parameter opsional. |
| extend | Aksi opsional untuk lebih lanjut mengkonfigurasi builder elemen elips. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
