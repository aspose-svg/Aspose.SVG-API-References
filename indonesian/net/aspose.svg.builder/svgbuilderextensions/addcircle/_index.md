---
title: "SVGBuilderExtensions.AddCircle"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddCircle. Menambahkan konfigurasi elemen circle ke builder."
type: docs
weight: 70
url: /id/net/aspose.svg.builder/svgbuilderextensions/addcircle/
---
## AddCircle<TBuilder>(*this TBuilder, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle_1}

Menambahkan konfigurasi elemen 'circle' ke builder.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    Action<SVGCircleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'circle'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddCircle<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle}

Menambahkan elemen 'circle' dengan pusat, radius, dan gaya yang ditentukan ke builder SVG.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGCircleElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi SVG builder ke mana elemen 'circle' akan ditambahkan. |
| cx | Koordinat x pusat lingkaran. Dapat berupa nilai double atau tuple double dan LengthType. |
| cy | Koordinat y pusat lingkaran. Dapat berupa nilai double atau tuple double dan LengthType. |
| r | Jari-jari lingkaran. Dapat berupa nilai double atau tuple double dan LengthType. |
| fill | Warna isi atau gaya cat untuk lingkaran. Dapat berupa Color atau nilai enum Paint atau ID server cat. Parameter opsional. |
| stroke | Warna garis tepi atau gaya cat untuk outline lingkaran. Dapat berupa Color atau nilai enum Paint atau ID server cat. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen lingkaran. Parameter opsional. |
| extend | Aksi opsional untuk lebih lanjut mengkonfigurasi builder elemen lingkaran. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
