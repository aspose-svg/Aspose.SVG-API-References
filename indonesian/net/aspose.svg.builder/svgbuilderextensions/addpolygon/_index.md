---
title: "SVGBuilderExtensions.AddPolygon"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddPolygon. Menambahkan konfigurasi elemen poligon ke builder"
type: docs
weight: 420
url: /id/net/aspose.svg.builder/svgbuilderextensions/addpolygon/
---
## AddPolygon<TBuilder>(*this TBuilder, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon_1}

Menambahkan konfigurasi elemen 'polygon' ke pembuat.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, 
    Action<SVGPolygonElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'polygon'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolygon<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon}

Menambahkan elemen 'polygon' ke pembuat SVG, menentukan verteksnya, dan gaya.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolygonElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi builder SVG tempat elemen 'polygon' akan ditambahkan. |
| titik | Array berisi nilai double yang mewakili titik-titik poligon (koordinat x dan y bergantian). |
| fill | Warna isi atau gaya cat untuk poligon. Bisa berupa nilai enum Color atau Paint atau ID server cat. Parameter opsional. |
| stroke | Warna garis atau gaya cat untuk poligon. Bisa berupa nilai enum Color atau Paint atau ID server cat. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen poligon. Parameter opsional. |
| extend | Aksi opsional untuk lebih lanjut mengkonfigurasi builder elemen poligon. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
