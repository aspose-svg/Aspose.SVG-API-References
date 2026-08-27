---
title: "SVGBuilderExtensions.AddPolyline"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode AddPolyline SVGBuilderExtensions. Menambahkan konfigurasi elemen polyline ke builder."
type: docs
weight: 430
url: /id/net/aspose.svg.builder/svgbuilderextensions/addpolyline/
---
## AddPolyline<TBuilder>(*this TBuilder, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline_1}

Menambahkan konfigurasi elemen 'polyline' ke pembuat.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, 
    Action<SVGPolylineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'polyline'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolyline<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline}

Menambahkan elemen 'polyline' ke pembuat SVG, menentukan verteksnya, dan gaya.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolylineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi builder SVG tempat elemen 'polyline' akan ditambahkan. |
| titik | Array double yang mewakili titik-titik polyline (koordinat x dan y bergantian). |
| fill | Warna isi atau gaya cat untuk polyline. Bisa berupa nilai Color atau enum Paint atau ID server cat. Parameter opsional. |
| stroke | Warna garis atau gaya cat untuk polyline. Bisa berupa nilai Color atau enum Paint atau ID server cat. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen polyline. Parameter opsional. |
| extend | Tindakan opsional untuk mengkonfigurasi lebih lanjut builder elemen polyline. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
