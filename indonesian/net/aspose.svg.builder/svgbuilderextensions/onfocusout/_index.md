---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode SVGBuilderExtensions OnFocusOut. Menetapkan atribut acara onfocusout untuk menangani acara focus-out pada elemen."
type: docs
weight: 1460
url: /id/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

Mengatur atribut acara 'onfocusout' untuk menangakan peristiwa fokus-keluar pada elemen.

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Parameter | Deskripsi |
| --- | --- |
| TBuilder | Tipe dari builder elemen SVG. |
| builder | Builder elemen SVG. |
| nilai | Fungsi atau skrip JavaScript untuk dijalankan ketika elemen kehilangan fokus, biasanya sebelum acara 'onblur'. |

### Nilai Kembalian

Instansi builder untuk chaining.

## Catatan

Acara 'onfocusout' dipicu ketika sebuah elemen akan kehilangan fokus. Mirip dengan 'onfocusin', acara ini mendukung bubbling dan dapat digunakan untuk mendeteksi perubahan fokus pada elemen anak juga.

### Lihat Juga

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
