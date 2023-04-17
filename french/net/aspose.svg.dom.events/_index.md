---
title: Aspose.Svg.Dom.Events
second_title: Référence de l'API Aspose.SVG pour .NET
description: Le Aspose.Svg.Dom.Events lespace de noms fournit des objets pour tous les événements liés à la mise à jour du DOM. Il inclut labonnement à lobservation dinformations contextuelles spécifiques associées à lévénement ainsi que la construction dévénements personnalisés.
type: docs
weight: 80
url: /fr/net/aspose.svg.dom.events/
---
Le **Aspose.Svg.Dom.Events** l'espace de noms fournit des objets pour tous les événements liés à la mise à jour du DOM. Il inclut l'abonnement à l'observation d'informations contextuelles spécifiques associées à l'événement ainsi que la construction d'événements personnalisés.

## Des classes

| Classer | La description |
| --- | --- |
| [CustomEvent](./customevent/) | Les événements utilisant l'interface CustomEvent peuvent être utilisés pour transporter des données personnalisées. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | Le[`DocumentLoadErrorEvent`](../aspose.svg.dom.events/documentloaderrorevent/) se produit lorsque la ressource demandée n'est pas disponible. |
| [DOMEventHandler](./domeventhandler/) | Représente le rappel pour la gestion des événements. |
| [ErrorEvent](./errorevent/) | Le[`ErrorEvent`](../aspose.svg.dom.events/errorevent/) fournit des informations contextuelles sur une erreur qui s'est produite pendant l'exécution. |
| [Event](./event/) | Le[`Event`](../aspose.svg.dom.events/event/) est utilisé pour fournir des informations contextuelles sur un événement au gestionnaire traitant l'événement. |
| [FocusEvent](./focusevent/) | L'interface FocusEvent fournit des informations contextuelles spécifiques associées aux événements Focus. |
| [InputEvent](./inputevent/) | Les événements d'entrée sont envoyés sous forme de notifications chaque fois que le DOM est mis à jour. |
| [KeyboardEvent](./keyboardevent/) | L'interface KeyboardEvent fournit des informations contextuelles spécifiques associées aux périphériques clavier. Chaque événement de clavier fait référence à une touche à l'aide d'une valeur. Les événements de clavier sont généralement dirigés vers l'élément qui a le focus. |
| [MouseEvent](./mouseevent/) | L'interface MouseEvent fournit des informations contextuelles spécifiques associées aux événements de souris. |
| [UIEvent](./uievent/) | L'interface UIEvent fournit des informations contextuelles spécifiques associées aux événements de l'interface utilisateur. |
| [WheelEvent](./wheelevent/) | L'interface WheelEvent fournit des informations contextuelles spécifiques associées aux événements de roue. Pour créer une instance de l'interface WheelEvent, utilisez le constructeur WheelEvent, en transmettant un dictionnaire WheelEventInit facultatif. |
## Interfaces

| Interface | La description |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | Le[`IDocumentEvent`](../aspose.svg.dom.events/idocumentevent/) fournit un mécanisme par lequel l'utilisateur peut créer un[`Event`](../aspose.svg.dom.events/event/) d'un type pris en charge par l'implémentation. |
| [IEventListener](./ieventlistener/) | Le[`IEventListener`](../aspose.svg.dom.events/ieventlistener/)l'interface est la principale méthode de gestion des événements. Les utilisateurs implémentent[`IEventListener`](../aspose.svg.dom.events/ieventlistener/) interface et enregistrer son auditeur sur une[`EventTarget`](../aspose.svg.dom/eventtarget/) en utilisant le[`AddEventListener`](../aspose.svg.dom/eventtarget/addeventlistener/) method. Les utilisateurs doivent également supprimer leur[`IEventListener`](../aspose.svg.dom.events/ieventlistener/) de son[`EventTarget`](../aspose.svg.dom/eventtarget/) après avoir terminé d'utiliser l'écouteur. |
| [IEventTarget](./ieventtarget/) | Le[`EventTarget`](../aspose.svg.dom/eventtarget/) est implémentée par tous les nœuds dans une implémentation qui prend en charge le modèle d'événement DOM. Par conséquent, cette interface peut être obtenue en utilisant des méthodes de conversion spécifiques à la liaison sur une instance de l'interface de nœud. L'interface permet l'enregistrement et la suppression des écouteurs d'événement sur un[`EventTarget`](../aspose.svg.dom/eventtarget/) et l'envoi d'événements à ce[`IEventTarget`](../aspose.svg.dom.events/ieventtarget/) . |


