---
title: IEventTarget.DispatchEvent
second_title: Référence de l'API Aspose.SVG pour .NET
description: IEventTarget méthode. Cette méthode permet de répartir les événements dans le modèle dévénement des implémentations.
type: docs
weight: 20
url: /fr/net/aspose.svg.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Cette méthode permet de répartir les événements dans le modèle d'événement des implémentations.

```csharp
public bool DispatchEvent(Event @event)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| event | Event | Spécifie le type d'événement, le comportement et les informations contextuelles à utiliser lors du traitement de l'événement. |

### Return_Value

La valeur de retour de[`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) indique si l'un des écouteurs qui a géré l'événement appelé[`PreventDefault`](../../event/preventdefault/) . Si[`PreventDefault`](../../event/preventdefault/) a été appelé la valeur est fausse, sinon la valeur est vraie.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) |  |

### Remarques

Les événements distribués de cette manière auront le même comportement de capture et de propagation que les événements distribués directement par l'implémentation. La cible de l'événement est le[`EventTarget`](../../../aspose.svg.dom/eventtarget/) sur lequel[`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) s'appelle.

### Voir également

* class [Event](../../event/)
* interface [IEventTarget](../)
* espace de noms [Aspose.Svg.Dom.Events](../../ieventtarget/)
* Assemblée [Aspose.SVG](../../../)


