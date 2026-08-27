---
title: "ResourceHandler.HandleResourceReference"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode ResourceHandler HandleResourceReference. Metode ini bertanggung jawab untuk menangani referensi sumber daya. Dalam metode ini Anda dapat menentukan seperti apa referensi ke sumber daya yang sedang ditangani."
type: docs
weight: 20
url: /id/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Metode ini bertanggung jawab untuk menangani referensi sumber daya. Dalam metode ini, Anda dapat menentukan seperti apa referensi ke sumber daya yang sedang ditangani.

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resource | Resource | [`Resource`](../../../aspose.svg.saving/resource/) yang akan ditangani. |
| context | ResourceHandlingContext | Konteks penanganan resource. |

### Nilai Kembalian

String yang akan ditulis ke sumber daya induk dan yang mewakili referensi ke sumber daya yang sedang ditangani.

### Pengecualian

| exception | kondisi |
| --- | --- |
| InvalidOperationException | Muncul jika [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) bernilai `null` dan [`Status`](../../../aspose.svg.saving/resource/status/) adalah Saved. [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) harus ditentukan untuk sumber daya yang disimpan karena jika tidak tidak mungkin menentukan referensi yang tepat dalam sumber daya yang merujuk ke yang ini. |

### Lihat Juga

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
