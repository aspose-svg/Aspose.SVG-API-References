---
title: "Kelas FileSystemResourceHandler"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Kelas Aspose.Svg.Saving.ResourceHandlers.FileSystemResourceHandler. Kelas ini merupakan implementasi dari kelas ResourceHandler yang dirancang untuk menyimpan sumber daya ke sistem file lokal"
type: docs
weight: 5720
url: /id/net/aspose.svg.saving.resourcehandlers/filesystemresourcehandler/
---
## FileSystemResourceHandler class

Kelas ini merupakan implementasi dari kelas [`ResourceHandler`](../resourcehandler/) yang dirancang untuk menyimpan sumber daya ke sistem file lokal.

```csharp
public class FileSystemResourceHandler : ResourceHandler
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor_1)(*string*) | Menginisialisasi instance baru dari kelas `FileSystemResourceHandler`. |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor)(*[Url](../../aspose.svg/url/)*) | Menginisialisasi instance baru dari kelas `FileSystemResourceHandler`. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [HandleResource](../../aspose.svg.saving.resourcehandlers/filesystemresourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Metode ini bertanggung jawab untuk menangani sumber daya. Di dalamnya Anda dapat menyimpan [`Resource`](../../aspose.svg.saving/resource/) ke aliran atau menyematkannya ke sumber daya induk. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Metode ini bertanggung jawab untuk menangani referensi sumber daya. Dalam metode ini, Anda dapat menentukan seperti apa referensi ke sumber daya yang sedang ditangani. |

### Lihat Juga

* class [ResourceHandler](../resourcehandler/)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
