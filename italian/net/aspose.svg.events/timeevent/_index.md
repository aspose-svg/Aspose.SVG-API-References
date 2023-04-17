---
title: Class TimeEvent
second_title: Riferimento API Aspose.SVG per .NET
description: Aspose.Svg.Events.TimeEvent classe. Linterfaccia TimeEvent fornisce informazioni contestuali specifiche associate agli eventi Time. I diversi tipi di eventi che possono verificarsi sono beginEvent endEvent e repeatEvent.
type: docs
weight: 1630
url: /it/net/aspose.svg.events/timeevent/
---
## TimeEvent class

L'interfaccia TimeEvent fornisce informazioni contestuali specifiche associate agli eventi Time. I diversi tipi di eventi che possono verificarsi sono: beginEvent, endEvent e repeatEvent.

```csharp
public class TimeEvent : Event
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Utilizzato per indicare se un evento è un evento bubbling. Se l'evento può generare bolle, il valore è vero, altrimenti il valore è falso. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Usato per indicare se un evento può avere o meno la sua azione predefinita prevenuta. Se l'azione predefinita può essere impedita, il valore è true, altrimenti il valore è false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Usato per indicare il[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) di chi[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) s sono attualmente in fase di elaborazione. Questo è particolarmente utile durante l'acquisizione e il bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Restituisce true se preventDefault() è stato richiamato mentre il valore dell'attributo cancelable è true, false in caso contrario. |
| [Detail](../../aspose.svg.events/timeevent/detail/) { get; } | Specifica alcune informazioni dettagliate sull'evento, a seconda del tipo di evento. Per questo tipo di evento, indica il numero di ripetizioni per l'animazione. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Utilizzato per indicare quale fase del flusso di eventi è attualmente in fase di valutazione. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | L'attributo isTrusted deve restituire il valore a cui è stato inizializzato. Quando viene creato un evento, l'attributo deve essere inizializzato su false. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Usato per indicare il[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) a cui l'evento è stato originariamente inviato. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Utilizzato per specificare l'ora (in millisecondi rispetto all'epoca) in cui è stato creato l'evento. A causa del fatto che alcuni sistemi potrebbero non fornire queste informazioni, il valore di timeStamp potrebbe non essere disponibile per tutti gli eventi. Quando non disponibile , verrà restituito un valore pari a 0. Esempi di epoch time sono l'ora di avvio del sistema o 0:0:0 UTC 1 gennaio 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Il nome dell'evento (senza distinzione tra maiuscole e minuscole). Il nome deve essere un nome XML. |
| [View](../../aspose.svg.events/timeevent/view/) { get; } | L'attributo view identifica l'AbstractView [DOM2VIEWS] da cui è stato generato l'evento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | Il[`InitEvent`](../../aspose.svg.dom.events/event/initevent/) Il metodo viene utilizzato per inizializzare il valore di an[`Event`](../../aspose.svg.dom.events/event/) creato tramite the [`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/) interfaccia. |
| [InitTimeEvent](../../aspose.svg.events/timeevent/inittimeevent/)(string, IAbstractView, long) | Il metodo initTimeEvent viene utilizzato per inizializzare il valore di un TimeEvent creato tramite l'interfaccia DocumentEvent. Questo metodo può essere chiamato solo prima che TimeEvent sia stato inviato tramite il metodo dispatchEvent, sebbene possa essere chiamato più volte durante quella fase, se necessario. Se chiamato più volte, l'invocazione finale ha la precedenza. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Se un evento è cancellabile, il[`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/) Il metodo viene utilizzato per indicare che l'evento deve essere annullato, il che significa che qualsiasi azione predefinita normalmente intrapresa dall'implementazione come risultato dell'evento non si verificherà. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | L'invocazione di questo metodo impedisce all'evento di raggiungere qualsiasi ascoltatore di eventi registrato dopo quello corrente e quando inviato in un albero impedisce anche all'evento di raggiungere qualsiasi altro oggetto. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Il[`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/) viene utilizzato il metodo per impedire l'ulteriore propagazione di un evento durante il flusso di eventi. |

### Guarda anche

* class [Event](../../aspose.svg.dom.events/event/)
* spazio dei nomi [Aspose.Svg.Events](../../aspose.svg.events/)
* assemblea [Aspose.SVG](../../)


