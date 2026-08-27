---
title: "Resource.Embed"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode Resource Embed. Menyematkan resource ini ke dalam induknya dengan mengkodekannya sebagai Base64. Hasil pengkodean akan ditulis ke OutputUrl"
type: docs
weight: 60
url: /id/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

Menyematkan resource ini ke dalam induknya dengan mengkodekannya sebagai Base64. Hasil pengkodean akan ditulis ke [`OutputUrl`](../outputurl/).

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| context | ResourceHandlingContext | Konteks penanganan resource. |

### Nilai Kembalian

Resource ini sehingga Anda dapat menyambung panggilan.

### Pengecualian

| exception | kondisi |
| --- | --- |
| InvalidOperationException | Dikeluarkan jika tidak ada [`ParentResource`](../../resourcehandlingcontext/parentresource/) karena tidak ada tempat untuk menyematkan hasil. |

### Lihat Juga

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
