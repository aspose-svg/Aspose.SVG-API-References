---
title: Class ErrorEvent
second_title: Référence de l'API Aspose.SVG pour .NET
description: Aspose.Svg.Dom.Events.ErrorEvent classe. LeErrorEvent fournit des informations contextuelles sur une erreur qui sest produite pendant lexécution.
type: docs
weight: 910
url: /fr/net/aspose.svg.dom.events/errorevent/
---
## ErrorEvent class

Le`ErrorEvent` fournit des informations contextuelles sur une erreur qui s'est produite pendant l'exécution.

```csharp
public class ErrorEvent : Event
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(Exception) | Initialise une nouvelle instance du`ErrorEvent` classe. |
| [ErrorEvent](errorevent/#constructor)(IDictionary&lt;string, object&gt;) | Initialise une nouvelle instance du`ErrorEvent` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Utilisé pour indiquer si un événement est un événement bouillonnant ou non. Si l'événement peut faire des bulles, la valeur est true, sinon la valeur est false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Utilisé pour indiquer si un événement peut ou non voir son action par défaut empêchée. Si l'action par défaut peut être empêchée, la valeur est true, sinon la valeur est false. |
| [ColNo](../../aspose.svg.dom.events/errorevent/colno/) { get; } | L'attribut colno doit renvoyer la valeur à laquelle il a été initialisé. Lors de la création de l'objet, cet attribut doit être initialisé à zéro. Il représente le numéro de colonne où l'erreur s'est produite dans le script. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Utilisé pour indiquer le[`IEventTarget`](../ieventtarget/) dont[`IEventListener`](../ieventlistener/) s sont en cours de traitement. Ceci est particulièrement utile lors de la capture et du bouillonnement. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Renvoie true si preventDefault() a été invoqué alors que la valeur de l'attribut annulable est true, et false sinon. |
| [Error](../../aspose.svg.dom.events/errorevent/error/) { get; } | L'attribut d'erreur doit renvoyer la valeur à laquelle il a été initialisé. Lorsque l'objet est créé, cet attribut doit être initialisé à null. Le cas échéant, il est défini sur l'objet représentant l'erreur (par exemple, l'objet d'exception dans le cas d'une exception DOM non interceptée). |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Utilisé pour indiquer quelle phase du flux d'événements est actuellement en cours d'évaluation. |
| [FileName](../../aspose.svg.dom.events/errorevent/filename/) { get; } | L'attribut filename doit renvoyer la valeur à laquelle il a été initialisé. Lorsque l'objet est créé, cet attribut doit être initialisé avec la chaîne vide. Il représente l'URL absolue du script dans lequel l'erreur s'est produite à l'origine. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | L'attribut isTrusted doit renvoyer la valeur à laquelle il a été initialisé. Lorsqu'un événement est créé, l'attribut doit être initialisé à false. |
| [LineNo](../../aspose.svg.dom.events/errorevent/lineno/) { get; } | L'attribut lineno doit renvoyer la valeur à laquelle il a été initialisé. Lors de la création de l'objet, cet attribut doit être initialisé à zéro. Il représente le numéro de ligne où l'erreur s'est produite dans le script. |
| [Message](../../aspose.svg.dom.events/errorevent/message/) { get; } | L'attribut de message doit renvoyer la valeur à laquelle il a été initialisé. Lorsque l'objet est créé, cet attribut doit être initialisé avec la chaîne vide. Il représente le message d'erreur. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Utilisé pour indiquer le[`IEventTarget`](../ieventtarget/) auquel l'événement a été envoyé à l'origine. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Utilisé pour spécifier l'heure (en millisecondes par rapport à l'époque) à laquelle l'événement a été créé. En raison du fait que certains systèmes peuvent ne pas fournir ces informations, la valeur de timeStamp peut ne pas être disponible pour tous les événements. Lorsqu'il n'est pas disponible , une valeur de 0 sera renvoyée. Des exemples d'heure d'époque sont l'heure de démarrage du système ou 0:0:0 UTC le 1er janvier 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Le nom de l'événement (insensible à la casse). Le nom doit être un nom XML. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | Le[`InitEvent`](../event/initevent/) méthode est utilisée pour initialiser la valeur d'un[`Event`](../event/) créé via the [`IDocumentEvent`](../idocumentevent/) interface. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Si un événement est annulable, le[`PreventDefault`](../event/preventdefault/) est utilisée pour signifier que l'événement doit être annulé, ce qui signifie que toute action par défaut normalement entreprise par l'implémentation à la suite de l'événement ne se produira pas. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | L'appel de cette méthode empêche l'événement d'atteindre les écouteurs d'événement enregistrés après celui en cours et, lorsqu'il est distribué dans une arborescence, empêche également l'événement d'atteindre tout autre objet. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Le[`StopPropagation`](../event/stoppropagation/) méthode est utilisée pour empêcher la propagation ultérieure d'un événement pendant le flux d'événements. |

### Voir également

* class [Event](../event/)
* espace de noms [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* Assemblée [Aspose.SVG](../../)


