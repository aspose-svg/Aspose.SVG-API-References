---
title: "SVGBuilderExtensions.AddImage"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddImage. Menambahkan konfigurasi elemen gambar ke pembangun"
type: docs
weight: 330
url: /id/net/aspose.svg.builder/svgbuilderextensions/addimage/
---
## AddImage<TBuilder>(*this TBuilder, Action&lt;SVGImageElementBuilder&gt;*) {#addimage}

Menambahkan konfigurasi elemen 'image' ke pembuat.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, 
    Action<SVGImageElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'image'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddImage<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, string, Action&lt;SVGImageElementBuilder&gt;*) {#addimage_1}

Menambahkan elemen 'image' ke pembuat SVG, menyematkan gambar eksternal ke dalam dokumen SVG.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, string id = null, 
    Action<SVGImageElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe builder elemen SVG, memfasilitasi penggunaan API yang lancar. |
| builder | Instansi pembangun SVG yang akan ditambahkan elemen 'image'. |
| href | URL atau referensi ke gambar eksternal. Parameter opsional. |
| x | Koordinat x tempat gambar ditempatkan. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| y | Koordinat y tempat gambar ditempatkan. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| width | Lebar gambar. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| height | Tinggi gambar. Dapat berupa double atau ValueTuple dengan LengthType. Parameter opsional. |
| id | Pengidentifikasi unik untuk elemen gambar. Parameter opsional. |
| extend | Tindakan opsional untuk lebih mengkonfigurasi SVGImageElementBuilder. |

### Nilai Kembalian

Instansi builder, memungkinkan chaining metode.

### Lihat Juga

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
