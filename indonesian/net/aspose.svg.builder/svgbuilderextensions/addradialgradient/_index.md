---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddRadialGradient. Menambahkan konfigurasi elemen radialGradient ke builder."
type: docs
weight: 440
url: /id/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

Menambahkan konfigurasi elemen 'radialGradient' ke pembuat.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'radialGradient'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

Menambahkan elemen 'radialGradient' ke pembuat SVG, menentukan pusat, radius, dan titik fokus, serta properti gradien lainnya.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi builder SVG yang akan ditambahkan elemen 'radialGradient'. |
| cx | Koordinat x dari pusat gradien. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| cy | Koordinat y dari pusat gradien. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| r | Jari-jari gradien. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| fx | Koordinat x dari titik fokus gradien. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| fy | Koordinat y dari titik fokus gradien. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| gradientUnits | Menentukan sistem koordinat untuk gradien. Parameter opsional. |
| spreadMethod | Mendefinisikan bagaimana gradien menyebar di luar titik mulai dan akhir. Parameter opsional. |
| href | Referensi ke gradien lain, jika berlaku. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen gradien. Parameter opsional. |
| extend | Tindakan opsional untuk lebih mengkonfigurasi pembangun elemen gradien radial. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
