---
title: "Classe Resource"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Classe Aspose.Svg.Saving.Resource. Cette classe décrit une ressource et fournit des méthodes pour la traiter"
type: docs
weight: 5710
url: /fr/net/aspose.svg.saving/resource/
---
## Resource class

Cette classe décrit une ressource et fournit des méthodes pour la traiter.

```csharp
public class Resource
```

## Propriétés

| Nom | Description |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | Renvoie le !:Html.MimeType de cette ressource. Peut être `null` si la ressource n'a pas été trouvée. |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | Renvoie une chaîne contenant la référence originale à cette ressource. |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | Renvoie une URL indiquant où cette ressource était située. |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | Obtient ou définit l'URL indiquant où la ressource sera située après le traitement. |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | Renvoie l'état actuel de la ressource. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | Intègre cette ressource dans son parent en l'encodant en Base64. Le résultat de l'encodage sera écrit dans [`OutputUrl`](./outputurl/). |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | Enregistre la ressource dans le flux fourni. |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | Spécifie la nouvelle URL indiquant où la ressource sera située après le traitement. |

### Voir aussi

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
