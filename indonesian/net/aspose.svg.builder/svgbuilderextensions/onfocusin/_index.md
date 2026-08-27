---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions OnFocusIn. Menetapkan atribut acara onfocusin untuk menangani peristiwa fokus-masuk pada elemen."
type: docs
weight: 1450
url: /id/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

Mengatur atribut acara 'onfocusin' untuk menangani peristiwa fokus-masuk pada elemen.

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| nilai | Fungsi atau skrip JavaScript yang dijalankan ketika elemen menerima fokus, biasanya sebelum acara 'onfocus'. |

### Nilai Kembalian

Instansi builder untuk chaining.

## Catatan

Peristiwa 'onfocusin' dipicu ketika sebuah elemen akan menerima fokus. Peristiwa ini berbeda dari 'onfocus' karena mendukung bubbling dan dapat digunakan untuk mendeteksi perubahan fokus pada elemen anak juga.

### Lihat Juga

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
