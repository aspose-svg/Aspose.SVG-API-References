---
title: "SVGBuilderExtensions.AddLine"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddLine. Menambahkan konfigurasi elemen line ke builder"
type: docs
weight: 350
url: /id/net/aspose.svg.builder/svgbuilderextensions/addline/
---
## AddLine<TBuilder>(*this TBuilder, Action&lt;SVGLineElementBuilder&gt;*) {#addline_1}

Menambahkan konfigurasi elemen 'line' ke pembuat.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    Action<SVGLineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'line'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLine<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGLineElementBuilder&gt;*) {#addline}

Menambahkan elemen 'line' dengan titik awal dan akhir yang ditentukan, serta gaya ke pembuat SVG.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1 = null, OneOf<double, (double, LengthType)> y1 = null, 
    OneOf<double, (double, LengthType)> x2 = null, OneOf<double, (double, LengthType)> y2 = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGLineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi builder SVG ke mana elemen 'line' akan ditambahkan. |
| x1 | Koordinat x dari titik awal line. Dapat berupa nilai double atau tuple double dan LengthType. |
| y1 | Koordinat y dari titik awal line. Dapat berupa nilai double atau tuple double dan LengthType. |
| x2 | Koordinat x dari titik akhir line. Dapat berupa nilai double atau tuple double dan LengthType. |
| y2 | Koordinat y dari titik akhir line. Dapat berupa nilai double atau tuple double dan LengthType. |
| fill | Warna isi atau gaya cat untuk line. Dapat berupa Color atau nilai enum Paint atau ID server cat. Parameter opsional. |
| stroke | Warna garis atau gaya cat untuk line. Dapat berupa Color atau nilai enum Paint atau ID server cat. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen line. Parameter opsional. |
| extend | Aksi opsional untuk lebih mengkonfigurasi builder elemen line. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
