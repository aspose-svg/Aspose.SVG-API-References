---
title: "Classe MediaQueryList"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Window.MediaQueryList. Un oggetto MediaQueryList memorizza informazioni su una query media applicata a un documento con supporto sia per il matching immediato sia per quello basato su eventi rispetto allo stato del documento. Vedere la specifica del modulo CSSOM View https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /it/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

Un oggetto MediaQueryList memorizza informazioni su una query media applicata a un documento, con supporto sia per il matching immediato sia per quello basato su eventi rispetto allo stato del documento. Vedere la specifica del modulo CSSOM View: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | Documento associato all'oggetto Context. |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | Un valore booleano che restituisce true se il documento corrisponde attualmente alla lista di query media, o false in caso contrario. |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | Una stringa che rappresenta una query media serializzata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al bersaglio. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al bersaglio. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al bersaglio. |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Aggiungi listener per l'evento di cambio stato di corrispondenza MediaQueryList. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Esegue la distribuzione di un Event all'[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) specificato, (sincronamente) invocando gli EventListeners interessati nell'ordine appropriato. Le regole normali di elaborazione degli eventi (inclusi la fase di cattura e quella di bubbling opzionale) si applicano anche agli eventi distribuiti manualmente con [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare il tipo di oggetto ECMAScript. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) viene rimosso da un [`EventTarget`](../../aspose.svg.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) viene rimosso da un [`EventTarget`](../../aspose.svg.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) viene rimosso da un [`EventTarget`](../../aspose.svg.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Rimuovi listener per l'evento di cambio stato di corrispondenza MediaQueryList. |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | Evento che viene generato sul MediaQueryList quando lo stato di corrispondenza cambia. |

### Vedi anche

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
