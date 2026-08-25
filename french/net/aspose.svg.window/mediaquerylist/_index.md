---
title: "Classe MediaQueryList"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Classe Aspose.Svg.Window.MediaQueryList. Un objet MediaQueryList stocke des informations sur une requête média appliquée à un document avec prise en charge à la fois du correspondance immédiate et basée sur les événements par rapport à l'état du document. Voir la spécification du module Vue CSSOM https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /fr/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

Un objet MediaQueryList stocke des informations sur une requête média appliquée à un document, avec prise en charge à la fois du correspondance immédiate et basée sur les événements par rapport à l'état du document. Voir la spécification du module Vue CSSOM : [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | Document associé à l'objet Context. |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | Une valeur booléenne qui renvoie true si le document correspond actuellement à la liste de requêtes média, ou false sinon. |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | Une chaîne représentant une requête média sérialisée. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Configure une fonction qui sera appelée chaque fois que l'événement spécifié est livré à la cible. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Configure une fonction qui sera appelée chaque fois que l'événement spécifié est livré à la cible. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Configure une fonction qui sera appelée chaque fois que l'événement spécifié est livré à la cible. |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Ajouter un écouteur d'événement de changement d'état de correspondance MediaQueryList. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Déclenche un Event sur le [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) spécifié, (synchroniquement) en invoquant les EventListeners concernés dans l'ordre approprié. Les règles normales de traitement des événements (y compris la phase de capture et la phase de propagation (bubbling)) s'appliquent également aux événements déclenchés manuellement avec [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer le type d'objet ECMAScript. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Cette méthode permet la suppression des écouteurs d'événements du cible d'événement. Si un [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) est retiré d'un [`EventTarget`](../../aspose.svg.dom/eventtarget/) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Cette méthode permet la suppression des écouteurs d'événements du cible d'événement. Si un [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) est retiré d'un [`EventTarget`](../../aspose.svg.dom/eventtarget/) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Cette méthode permet la suppression des écouteurs d'événements du cible d'événement. Si un [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) est retiré d'un [`EventTarget`](../../aspose.svg.dom/eventtarget/) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Supprimer l'écouteur d'événement de changement d'état de correspondance MediaQueryList. |

## Événements

| Nom | Description |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | Événement déclenché sur le MediaQueryList lorsque l'état de correspondance change. |

### Voir aussi

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
