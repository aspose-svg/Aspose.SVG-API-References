---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "ResourceHandler HandleResourceReference methode. Deze methode is verantwoordelijk voor het verwerken van de resource-referentie. In deze methode kun je instellen hoe de referentie naar de verwerkte resource eruitziet."
type: docs
weight: 20
url: /nl/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Deze methode is verantwoordelijk voor het verwerken van de resource-referentie. In deze methode kun je instellen hoe de referentie naar de verwerkte resource eruitziet.

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resource | Resource | De [`Resource`](../../../aspose.svg.saving/resource/) die zal worden verwerkt. |
| context | ResourceHandlingContext | Resource handling context. |

### Retourwaarde

Een string die naar de bovenliggende resource wordt geschreven en die een referentie naar de momenteel verwerkte resource vertegenwoordigt.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| InvalidOperationException | Opgetreden als [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) `null` is en [`Status`](../../../aspose.svg.saving/resource/status/) Saved is. [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) moet worden opgegeven voor opgeslagen resources, omdat anders het onmogelijk is de juiste referentie op te geven in de resources die naar deze verwijzen. |

### Zie ook

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
