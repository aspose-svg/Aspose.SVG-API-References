---
title: "Resource.Embed"
second_title: "Aspose.SVG for .NET API Reference"
description: "Resource Embed yöntemi. Bu kaynağı, Base64 olarak kodlayarak üst öğesine gömer. Kodlama sonucu OutputUrl'ye yazılacaktır."
type: docs
weight: 60
url: /tr/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

Bu kaynağı, Base64 olarak kodlayarak üst öğesine gömer. Kodlama sonucu [`OutputUrl`](../outputurl/) adresine yazılacaktır.

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bağlam | ResourceHandlingContext | Kaynak işleme bağlamı. |

### Dönüş Değeri

Bu kaynak, çağrıları zincirlemenizi sağlar.

### İstisnalar

| istisna | koşul |
| --- | --- |
| InvalidOperationException | Sonucun gömülecek bir yeri olmadığı için [`ParentResource`](../../resourcehandlingcontext/parentresource/) bulunmadığında ortaya çıkar. |

### Ayrıca Bakınız

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
