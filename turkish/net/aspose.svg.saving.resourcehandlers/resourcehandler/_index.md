---
title: "ResourceHandler Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Saving.ResourceHandlers.ResourceHandler sınıfı. Bu sınıf, kaynakları işlemekten sorumludur. Kaynakla ne yapılacağını ve üst Resource'a hangi referansın yazılacağını kontrol etmenizi sağlayan yöntemler sunar."
type: docs
weight: 5730
url: /tr/net/aspose.svg.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

Bu sınıf, kaynakları işlemekten sorumludur. [`Resource`](../../aspose.svg.saving/resource/) ile ne yapılacağını ve üst [`Resource`](../../aspose.svg.saving/resource/) içine hangi referansın yazılacağını kontrol etmenizi sağlayan yöntemler sunar.

```csharp
public abstract class ResourceHandler
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| abstract [HandleResource](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Bu yöntem, kaynağı işlemekten sorumludur. Bu yöntemde, [`Resource`](../../aspose.svg.saving/resource/) akışa kaydedebilir veya üst kaynağa gömebilirsiniz. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Bu yöntem, kaynak referansını işlemekten sorumludur. Bu yöntemde, işlenen kaynağa olan referansın nasıl görüneceğini ayarlayabilirsiniz. |

### Ayrıca Bakınız

* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
