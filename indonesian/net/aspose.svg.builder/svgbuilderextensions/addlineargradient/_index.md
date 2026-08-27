---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddLinearGradient. Menambahkan konfigurasi elemen linearGradient ke builder."
type: docs
weight: 360
url: /id/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

Menambahkan konfigurasi elemen 'linearGradient' ke pembuat.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'linearGradient'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

Menambahkan elemen 'linearGradient' ke pembuat SVG, menentukan posisi awal dan akhir, serta properti gradien lainnya.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi builder SVG yang akan ditambahkan elemen 'linearGradient'. |
| x1 | Koordinat x awal untuk gradien. Dapat berupa double atau ValueTuple dengan LengthType. |
| y1 | Koordinat y awal untuk gradien. Dapat berupa double atau ValueTuple dengan LengthType. |
| x2 | Koordinat x akhir untuk gradien. Dapat berupa double atau ValueTuple dengan LengthType. |
| y2 | Koordinat y akhir untuk gradien. Dapat berupa double atau ValueTuple dengan LengthType. |
| gradientUnits | Menentukan sistem koordinat untuk gradien. Parameter opsional. |
| spreadMethod | Mendefinisikan bagaimana gradien menyebar di luar titik mulai dan akhir. Parameter opsional. |
| href | Referensi ke gradien lain, jika berlaku. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen gradien. Parameter opsional. |
| extend | Aksi opsional untuk lebih lanjut mengkonfigurasi builder elemen linear gradient. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
