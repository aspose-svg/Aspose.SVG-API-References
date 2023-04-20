---
title: IDocumentEvent.CreateEvent
second_title: Référence de l'API Aspose.SVG pour .NET
description: IDocumentEvent méthode. Crée unEvent dun type pris en charge par limplémentation.
type: docs
weight: 10
url: /fr/net/aspose.svg.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Crée un[`Event`](../../event/) d'un type pris en charge par l'implémentation.

```csharp
public Event CreateEvent(string eventType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| eventType | String | Le paramètre eventType spécifie le type de[`Event`](../../event/) interface à créer.  Si le[`Event`](../../event/)l'interface spécifiée est prise en charge par l'implémentation cette méthode renverra un new [`Event`](../../event/) du type d'interface demandé. Si le[`Event`](../../event/)est à expédier via le[`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) méthode appropriée [`InitEvent`](../../event/initevent/) La méthode doit être appelée après la création afin d'initialiser la[`Event`](../../event/) s valeurs. |

### Return_Value

La nouvelle création[`Event`](../../event/)

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR : déclenché si l'implémentation ne prend pas en charge le type de[`Event`](../../event/) interface demandée |

### Voir également

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* espace de noms [Aspose.Svg.Dom.Events](../../idocumentevent/)
* Assemblée [Aspose.SVG](../../../)


