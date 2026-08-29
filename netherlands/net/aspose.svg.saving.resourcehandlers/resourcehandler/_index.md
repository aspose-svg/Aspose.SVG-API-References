---
title: "ResourceHandler Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Saving.ResourceHandlers.ResourceHandler class. Deze klasse is verantwoordelijk voor het verwerken van resources. Het biedt methoden die je in staat stellen te bepalen wat er met de Resource gebeurt en welke referentie naar de bovenliggende Resource wordt geschreven."
type: docs
weight: 5730
url: /nl/net/aspose.svg.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

Deze klasse is verantwoordelijk voor het verwerken van resources. Het biedt methoden die je in staat stellen te bepalen wat er met de [`Resource`](../../aspose.svg.saving/resource/) gebeurt, evenals welke referentie naar de bovenliggende [`Resource`](../../aspose.svg.saving/resource/) wordt geschreven.

```csharp
public abstract class ResourceHandler
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| abstract [HandleResource](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Deze methode is verantwoordelijk voor het verwerken van de resource. In deze kun je de [`Resource`](../../aspose.svg.saving/resource/) opslaan naar de stream of insluiten in de bovenliggende resource. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Deze methode is verantwoordelijk voor het verwerken van de resource-referentie. In deze methode kun je instellen hoe de referentie naar de verwerkte resource eruitziet. |

### Zie ook

* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
