---
title: "Resource.Embed"
second_title: "Aspose.SVG för .NET API-referens"
description: "Resource Embed-metoden. Bäddar in denna resurs i sin förälder genom att koda den som Base64. Kodningsresultatet kommer att skrivas till OutputUrl"
type: docs
weight: 60
url: /sv/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

Bäddar in denna resurs i sin förälder genom att koda den som Base64. Kodningsresultatet kommer att skrivas till [`OutputUrl`](../outputurl/).

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| context | ResourceHandlingContext | Resurshanteringskontext. |

### Returvärde

Denna resurs så att du kan kedja anrop.

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidOperationException | Utlöst om det inte finns någon [`ParentResource`](../../resourcehandlingcontext/parentresource/) eftersom det inte finns någon plats att bädda in resultatet. |

### Se även

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
