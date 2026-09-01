---
title: "Kaynak Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Saving.Resource sınıfı. Bu sınıf bir kaynağı tanımlar ve onu işlemek için yöntemler sağlar"
type: docs
weight: 5710
url: /tr/net/aspose.svg.saving/resource/
---
## Resource class

Bu sınıf bir kaynağı tanımlar ve onu işlemek için yöntemler sağlar.

```csharp
public class Resource
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | Bu kaynağın !:Html.MimeType değerini döndürür. Kaynak bulunamazsa `null` olabilir. |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | Bu kaynağa olan orijinal referansı içeren bir dize döndürür. |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | Bu kaynağın nerede bulunduğunu gösteren bir URL döndürür. |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | Kaynağın işlendikten sonra nerede bulunacağını gösteren URL'yi alır veya ayarlar. |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | Kaynağın mevcut durumunu döndürür. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | Bu kaynağı, Base64 olarak kodlayarak üst öğesine gömer. Kodlama sonucu [`OutputUrl`](./outputurl/) adresine yazılacak. |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | Kaynağı sağlanan akıma kaydeder. |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | Kaynağın işlendikten sonra nerede bulunacağını gösteren yeni URL'yi belirtir. |

### Ayrıca Bakınız

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
