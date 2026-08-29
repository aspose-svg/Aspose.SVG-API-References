---
title: "FileSystemResourceHandler Class"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Saving.ResourceHandlers.FileSystemResourceHandler class. Deze klasse is een implementatie van de ResourceHandler-klasse ontworpen om bronnen op te slaan naar het lokale bestandssysteem."
type: docs
weight: 5720
url: /nl/net/aspose.svg.saving.resourcehandlers/filesystemresourcehandler/
---
## FileSystemResourceHandler class

Deze klasse is een implementatie van de [`ResourceHandler`](../resourcehandler/) klasse ontworpen om bronnen op te slaan naar het lokale bestandssysteem.

```csharp
public class FileSystemResourceHandler : ResourceHandler
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor_1)(*string*) | Initialiseert een nieuw exemplaar van de `FileSystemResourceHandler` klasse. |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor)(*[Url](../../aspose.svg/url/)*) | Initialiseert een nieuw exemplaar van de `FileSystemResourceHandler` klasse. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [HandleResource](../../aspose.svg.saving.resourcehandlers/filesystemresourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Deze methode is verantwoordelijk voor het verwerken van de resource. In deze kun je de [`Resource`](../../aspose.svg.saving/resource/) opslaan naar de stream of insluiten in de bovenliggende resource. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Deze methode is verantwoordelijk voor het verwerken van de resource-referentie. In deze methode kun je instellen hoe de referentie naar de verwerkte resource eruitziet. |

### Zie ook

* class [ResourceHandler](../resourcehandler/)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
