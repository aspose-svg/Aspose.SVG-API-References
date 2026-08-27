---
title: "Resource.Save"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode Resource Save. Menyimpan resource ke stream yang disediakan"
type: docs
weight: 70
url: /id/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

Menyimpan sumber daya ke aliran yang disediakan.

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran di mana resource akan disimpan. |
| context | ResourceHandlingContext | Konteks penanganan resource. |

### Nilai Kembalian

Resource ini sehingga Anda dapat menyambung panggilan.

### Pengecualian

| exception | kondisi |
| --- | --- |
| InvalidOperationException | Dikeluarkan jika [`OutputUrl`](../outputurl/) bernilai `null`. [`OutputUrl`](../outputurl/) harus ditentukan sebelum menyimpan resource karena jika tidak tidak mungkin menentukan referensi yang tepat dalam resource yang merujuk ke yang ini. |

### Lihat Juga

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
