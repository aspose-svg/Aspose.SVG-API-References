---
title: "SVGBuilderExtensions.AddText"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions AddText. Menambahkan konfigurasi elemen teks ke pembuat."
type: docs
weight: 530
url: /id/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

Menambahkan konfigurasi elemen 'text' ke builder.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Instansi builder. |
| konfigurasi | Aksi konfigurasi untuk elemen 'text'. |

### Nilai Kembalian

Instansi builder untuk chaining.

### Lihat Juga

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

Menambahkan elemen 'text' dengan konten dan atribut yang ditentukan ke builder SVG.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe pembuat elemen SVG, memungkinkan chaining. |
| builder | Instansi pembuat tempat elemen 'text' akan ditambahkan. |
| content | Konten teks yang akan ditampilkan di dalam elemen 'text'. |
| x | Koordinat x untuk elemen teks. Dapat berupa nilai double atau tuple dari double dan LengthType. |
| y | Koordinat y untuk elemen teks. Dapat berupa nilai double atau tuple dari double dan LengthType. |
| fontSize | Ukuran font untuk teks. Dapat berupa nilai double atau tuple dari double dan LengthType. |
| fontStyle | Gaya font untuk teks (mis., normal, italic, oblique). |
| fontFamily | Keluarga font untuk teks (mis., Arial, Verdana). |
| fontWeight | Berat (ketebalan) font (mis., normal, tebal). |
| fill | Warna isi atau gaya cat untuk teks. Dapat berupa Color atau nilai enum Paint atau ID server cat. |
| stroke | Warna garis atau gaya cat untuk teks. Dapat berupa Color atau nilai enum Paint atau ID server cat. |
| id | Pengidentifikasi unik untuk elemen teks. |
| extend | Aksi opsional untuk lebih mengonfigurasi pembangun elemen teks. |

### Nilai Kembalian

Instansi pembangun untuk menambahkan atau mengonfigurasi lebih lanjut secara berantai.

### Lihat Juga

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
