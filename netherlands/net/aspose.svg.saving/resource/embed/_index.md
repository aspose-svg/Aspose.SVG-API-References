---
title: "Resource.Embed"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Resource Embed-methode. Integreert deze resource in zijn ouder door deze te coderen als Base64. Het coderingsresultaat wordt geschreven naar OutputUrl."
type: docs
weight: 60
url: /nl/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

Integreert deze resource in zijn ouder door deze te coderen als Base64. Het coderingsresultaat wordt geschreven naar [`OutputUrl`](../outputurl/).

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| context | ResourceHandlingContext | Resource handling context. |

### Retourwaarde

Deze resource zodat u keten‑aanroepen kunt doen.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| InvalidOperationException | Wordt opgegooid als er geen [`ParentResource`](../../resourcehandlingcontext/parentresource/) is omdat er nergens is om het resultaat in te voegen. |

### Zie ook

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
