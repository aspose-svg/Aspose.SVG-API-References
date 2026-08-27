---
title: "Antarmuka IStorage"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Antarmuka Aspose.Svg.Dom.IStorage. Antarmuka ini dari Web Storage API menyediakan akses ke sesi atau penyimpanan lokal domain tertentu. Lihat spesifikasi Web Storage https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /id/net/aspose.svg.dom/istorage/
---
## IStorage interface

Antarmuka ini dari Web Storage API menyediakan akses ke sesi atau penyimpanan lokal domain tertentu. Lihat spesifikasi Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | Mengembalikan jumlah pasangan kunci/nilai. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | Menghapus semua pasangan kunci/nilai, jika ada. |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | Mengembalikan nilai saat ini yang terkait dengan kunci yang diberikan, atau null jika kunci yang diberikan tidak ada. |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | Mengembalikan nama kunci ke-n, atau null jika n lebih besar atau sama dengan jumlah pasangan kunci/nilai. |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | Menghapus pasangan kunci/nilai dengan kunci yang diberikan, jika pasangan kunci/nilai dengan kunci tersebut ada. |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | Menetapkan nilai pasangan yang diidentifikasi oleh kunci menjadi nilai, membuat pasangan kunci/nilai baru jika sebelumnya tidak ada pasangan untuk kunci tersebut. |

### Lihat Juga

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
