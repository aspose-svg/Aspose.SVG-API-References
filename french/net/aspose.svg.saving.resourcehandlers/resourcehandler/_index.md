---
title: "Classe ResourceHandler"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Classe Aspose.Svg.Saving.ResourceHandlers.ResourceHandler. Cette classe est responsable du traitement des ressources. Elle fournit des méthodes qui vous permettent de contrôler ce qui sera fait avec la Resource ainsi que la référence qui sera écrite dans la Resource parente."
type: docs
weight: 5730
url: /fr/net/aspose.svg.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

Cette classe est responsable du traitement des ressources. Elle fournit des méthodes qui vous permettent de contrôler ce qui sera fait avec le [`Resource`](../../aspose.svg.saving/resource/), ainsi que la référence qui sera écrite dans le [`Resource`](../../aspose.svg.saving/resource/) parent.

```csharp
public abstract class ResourceHandler
```

## Méthodes

| Nom | Description |
| --- | --- |
| abstract [HandleResource](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Cette méthode est responsable du traitement de la ressource. Dans celle‑ci, vous pouvez enregistrer le [`Resource`](../../aspose.svg.saving/resource/) dans le flux ou l’intégrer à la ressource parente. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Cette méthode est responsable du traitement de la référence de la ressource. Dans cette méthode, vous pouvez définir à quoi ressemblera la référence à la ressource traitée. |

### Voir aussi

* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
