---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode ResourceHandler HandleResourceReference. Cette méthode est responsable du traitement de la référence de ressource. Dans cette méthode, vous pouvez définir à quoi ressemblera la référence à la ressource traitée."
type: docs
weight: 20
url: /fr/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Cette méthode est responsable du traitement de la référence de la ressource. Dans cette méthode, vous pouvez définir à quoi ressemblera la référence à la ressource traitée.

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| resource | Resource | Le [`Resource`](../../../aspose.svg.saving/resource/) qui sera traité. |
| contexte | ResourceHandlingContext | Contexte de gestion des ressources. |

### Valeur de retour

Une chaîne qui sera écrite dans la ressource parente et qui représente une référence à la ressource actuellement traitée.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Levée si [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) est `null` et que [`Status`](../../../aspose.svg.saving/resource/status/) est Saved. [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) doit être spécifié pour la ressource enregistrée car sinon il est impossible de spécifier la référence correcte dans les ressources qui référencent celle‑ci. |

### Voir aussi

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
