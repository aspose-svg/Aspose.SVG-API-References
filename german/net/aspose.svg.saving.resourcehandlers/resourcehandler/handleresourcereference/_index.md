---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "ResourceHandler HandleResourceReference Methode. Diese Methode ist für die Verarbeitung der Ressourcenreferenz verantwortlich. In dieser Methode können Sie festlegen, wie die Referenz auf die gerade verarbeitete Ressource aussehen soll."
type: docs
weight: 20
url: /de/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Diese Methode ist für die Verarbeitung der Ressourcenreferenz verantwortlich. In dieser Methode können Sie festlegen, wie die Referenz auf die zu verarbeitende Ressource aussehen soll.

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resource | Resource | Die [`Resource`](../../../aspose.svg.saving/resource/), die verarbeitet wird. |
| context | ResourceHandlingContext | Ressourcenverarbeitungskontext. |

### Rückgabewert

Ein String, der in die übergeordnete Ressource geschrieben wird und eine Referenz auf die aktuell verarbeitete Ressource darstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Wird ausgelöst, wenn [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) `null` ist und [`Status`](../../../aspose.svg.saving/resource/status/) auf Saved gesetzt ist. [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) sollte für gespeicherte Ressourcen angegeben werden, da sonst die korrekte Referenz in den Ressourcen, die auf diese verweisen, nicht angegeben werden kann. |

### Siehe auch

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
