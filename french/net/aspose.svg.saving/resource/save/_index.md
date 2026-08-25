---
title: "Resource.Save"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode Save de Resource. Enregistre la ressource dans le flux fourni."
type: docs
weight: 70
url: /fr/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

Enregistre la ressource dans le flux fourni.

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux dans lequel la ressource sera enregistrée. |
| contexte | ResourceHandlingContext | Contexte de gestion des ressources. |

### Valeur de retour

Cette ressource afin que vous puissiez chaîner les appels.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Levée si [`OutputUrl`](../outputurl/) est `null`. [`OutputUrl`](../outputurl/) doit être spécifié avant d'enregistrer la ressource car sinon il est impossible de spécifier la référence correcte dans les ressources qui référencent celle-ci. |

### Voir aussi

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
