---
title: "Classe FileSystemResourceHandler"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Classe Aspose.Svg.Saving.ResourceHandlers.FileSystemResourceHandler. Cette classe est une implémentation de la classe ResourceHandler conçue pour enregistrer des ressources sur le système de fichiers local"
type: docs
weight: 5720
url: /fr/net/aspose.svg.saving.resourcehandlers/filesystemresourcehandler/
---
## FileSystemResourceHandler class

Cette classe est une implémentation de la classe [`ResourceHandler`](../resourcehandler/) conçue pour enregistrer des ressources sur le système de fichiers local.

```csharp
public class FileSystemResourceHandler : ResourceHandler
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor_1)(*string*) | Initialise une nouvelle instance de la classe `FileSystemResourceHandler`. |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor)(*[Url](../../aspose.svg/url/)*) | Initialise une nouvelle instance de la classe `FileSystemResourceHandler`. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [HandleResource](../../aspose.svg.saving.resourcehandlers/filesystemresourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Cette méthode est responsable du traitement de la ressource. Dans celle‑ci, vous pouvez enregistrer le [`Resource`](../../aspose.svg.saving/resource/) dans le flux ou l’intégrer à la ressource parente. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Cette méthode est responsable du traitement de la référence de la ressource. Dans cette méthode, vous pouvez définir à quoi ressemblera la référence à la ressource traitée. |

### Voir aussi

* class [ResourceHandler](../resourcehandler/)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
