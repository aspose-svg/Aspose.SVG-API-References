---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.SVG för .NET API-referens"
description: "ResourceHandler HandleResourceReference-metoden. Denna metod ansvarar för att hantera resursreferensen. I den här metoden kan du ange hur referensen till den resurs som hanteras ska se ut."
type: docs
weight: 20
url: /sv/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Denna metod ansvarar för att hantera resursreferensen. I denna metod kan du ange hur referensen till den hanterade resursen ska se ut.

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resource | Resource | Den [`Resource`](../../../aspose.svg.saving/resource/) som kommer att hanteras. |
| context | ResourceHandlingContext | Resurshanteringskontext. |

### Returvärde

En sträng som kommer att skrivas till föräldraresursen och som representerar en referens till den resurs som för närvarande hanteras.

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidOperationException | Utlöst om [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) är `null` och [`Status`](../../../aspose.svg.saving/resource/status/) är Saved. [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) bör specificeras för sparad resurs eftersom det annars är omöjligt att ange korrekt referens i resurser som refererar till denna. |

### Se även

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
