---
title: "Resource.Save"
second_title: "Aspose.SVG for .NET API Reference"
description: "Resource Save yöntemi. Kaynağı sağlanan akıma kaydeder."
type: docs
weight: 70
url: /tr/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

Kaynağı sağlanan akıma kaydeder.

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akım | Akım | Kaynağın kaydedileceği akım. |
| bağlam | ResourceHandlingContext | Kaynak işleme bağlamı. |

### Dönüş Değeri

Bu kaynak, çağrıları zincirlemenizi sağlar.

### İstisnalar

| istisna | koşul |
| --- | --- |
| InvalidOperationException | [`OutputUrl`](../outputurl/) `null` ise ortaya çıkar. [`OutputUrl`](../outputurl/) kaynağı kaydetmeden önce belirtilmelidir; aksi takdirde bu kaynağa referans veren kaynaklarda doğru referansı belirtmek mümkün olmaz. |

### Ayrıca Bakınız

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
