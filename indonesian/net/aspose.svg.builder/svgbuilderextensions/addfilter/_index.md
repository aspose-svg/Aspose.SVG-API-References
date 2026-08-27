---
title: "SVGBuilderExtensions.AddFilter"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddFilter. Menambahkan konfigurasi elemen filter ke pembuat."
type: docs
weight: 300
url: /id/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

Menambahkan konfigurasi elemen 'filter' ke pembuat.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'filter'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

Menambahkan elemen 'filter' ke pembuat SVG, mendefinisikan efek filter yang dapat diterapkan pada elemen SVG.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi pembuat SVG yang akan ditambahkan elemen 'filter'. |
| filterUnits | Menentukan sistem koordinat untuk atribut x, y, lebar, dan tinggi filter. Parameter opsional. |
| primitiveUnits | Menentukan sistem koordinat untuk atribut elemen anak filter. Parameter opsional. |
| x | Koordinat x dari wilayah filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| y | Koordinat y dari wilayah filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| width | Lebar wilayah filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| height | Tinggi wilayah filter. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| fill | Warna isi atau cat untuk elemen filter. Parameter opsional. |
| stroke | Warna garis atau cat untuk elemen filter. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen filter. Parameter opsional. |
| extend | Aksi opsional untuk lebih mengonfigurasi SVGFilterElementBuilder. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
