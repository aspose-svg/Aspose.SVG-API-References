---
title: "Kelas Resource"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Kelas Aspose.Svg.Saving.Resource. Kelas ini menggambarkan sebuah sumber daya dan menyediakan metode untuk memprosesnya"
type: docs
weight: 5710
url: /id/net/aspose.svg.saving/resource/
---
## Resource class

Kelas ini mendeskripsikan sebuah sumber daya dan menyediakan metode untuk memprosesnya.

```csharp
public class Resource
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | Mengembalikan !:Html.MimeType dari sumber daya ini. Bisa `null` jika sumber daya tidak ditemukan. |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | Mengembalikan string yang berisi referensi asli ke sumber daya ini. |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | Mengembalikan URL yang menunjukkan lokasi sumber daya ini. |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | Mengambil atau mengatur URL yang menunjukkan di mana sumber daya akan berada setelah diproses. |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | Mengembalikan status terkini dari sumber daya. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | Menanamkan sumber daya ini ke dalam induknya dengan mengkodekannya sebagai Base64. Hasil enkoding akan ditulis ke [`OutputUrl`](./outputurl/). |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | Menyimpan sumber daya ke aliran yang disediakan. |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | Menentukan URL baru yang menunjukkan di mana sumber daya akan berada setelah diproses. |

### Lihat Juga

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
