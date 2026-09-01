---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.SVG for .NET API Reference"
description: "ResourceHandler HandleResourceReference yöntemi. Bu yöntem, kaynak referansını işlemekten sorumludur. Bu yöntemde işlenen kaynağa olan referansın nasıl görüneceğini ayarlayabilirsiniz."
type: docs
weight: 20
url: /tr/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Bu yöntem, kaynak referansını işlemekten sorumludur. Bu yöntemde, işlenen kaynağa olan referansın nasıl görüneceğini ayarlayabilirsiniz.

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resource | Resource | İşlenecek [`Resource`](../../../aspose.svg.saving/resource/). |
| bağlam | ResourceHandlingContext | Kaynak işleme bağlamı. |

### Dönüş Değeri

Üst kaynağa yazılacak ve şu anda işlenen kaynağa bir referansı temsil eden bir dize.

### İstisnalar

| istisna | koşul |
| --- | --- |
| InvalidOperationException | Eğer [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) `null` ise ve [`Status`](../../../aspose.svg.saving/resource/status/) Saved durumundaysa ortaya çıkar. Kaydedilen kaynak için [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) belirtilmelidir, aksi takdirde bu kaynağa başvuran kaynaklarda doğru referansı belirtmek mümkün olmaz. |

### Ayrıca Bakınız

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
