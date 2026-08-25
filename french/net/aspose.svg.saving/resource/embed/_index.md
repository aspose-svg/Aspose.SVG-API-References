---
title: "Resource.Embed"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode Embed de Resource. Intègre cette ressource dans son parent en l'encodant en Base64. Le résultat de l'encodage sera écrit dans OutputUrl."
type: docs
weight: 60
url: /fr/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

Intègre cette ressource dans son parent en l'encodant en Base64. Le résultat de l'encodage sera écrit dans [`OutputUrl`](../outputurl/).

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contexte | ResourceHandlingContext | Contexte de gestion des ressources. |

### Valeur de retour

Cette ressource afin que vous puissiez chaîner les appels.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Levée s'il n'existe pas de [`ParentResource`](../../resourcehandlingcontext/parentresource/) parce qu'il n'y a nulle part où intégrer le résultat. |

### Voir aussi

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
