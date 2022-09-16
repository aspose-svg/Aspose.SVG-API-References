---
title: WheelEvent
second_title: Riferimento API Aspose.SVG per .NET
description: Linterfaccia WheelEvent fornisce informazioni contestuali specifiche associate agli eventi ruota. Per creare unistanza dellinterfaccia WheelEvent utilizzare il costruttore WheelEvent passando un dizionario WheelEventInit facoltativo.
type: docs
weight: 1010
url: /it/net/aspose.svg.dom.events/wheelevent/
---
## WheelEvent class

L'interfaccia WheelEvent fornisce informazioni contestuali specifiche associate agli eventi ruota. Per creare un'istanza dell'interfaccia WheelEvent, utilizzare il costruttore WheelEvent, passando un dizionario WheelEventInit facoltativo.

```csharp
public class WheelEvent : MouseEvent
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WheelEvent](wheelevent#constructor)(string) | Inizializza una nuova istanza di[`WheelEvent`](../wheelevent) classe. |
| [WheelEvent](wheelevent#constructor_1)(string, IDictionary&lt;string, object&gt;) | Inizializza una nuova istanza di[`WheelEvent`](../wheelevent) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/mouseevent/altkey) { get; } | Fare riferimento all'attributo altKey. |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles) { get; } | Utilizzato per indicare se un evento è o meno un evento bubbling. Se l'evento può presentare bolle, il valore è true, altrimenti il valore è false. |
| [Button](../../aspose.svg.dom.events/mouseevent/button) { get; } | Durante gli eventi del mouse causati dalla pressione o dal rilascio di un pulsante del mouse, il pulsante DEVE essere utilizzato per indicare quale pulsante del dispositivo puntatore ha cambiato stato. |
| [Buttons](../../aspose.svg.dom.events/mouseevent/buttons) { get; } | Durante qualsiasi evento del mouse, i pulsanti DEVONO essere utilizzati per indicare quale combinazione di pulsanti del mouse è attualmente premuta, espressa come una maschera di bit. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable) { get; } | Utilizzato per indicare se a un evento può essere impedita o meno l'azione predefinita. Se è possibile impedire l'azione predefinita, il valore è true, altrimenti il valore è false. |
| [ClientX](../../aspose.svg.dom.events/mouseevent/clientx) { get; } | La coordinata orizzontale in cui si è verificato l'evento rispetto alla finestra associata all'evento. |
| [ClientY](../../aspose.svg.dom.events/mouseevent/clienty) { get; } | La coordinata verticale in cui si è verificato l'evento rispetto alla finestra associata all'evento. |
| [CtrlKey](../../aspose.svg.dom.events/mouseevent/ctrlkey) { get; } | Fare riferimento all'attributo ctrlKey. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget) { get; } | Usato per indicare il[`IEventTarget`](../ieventtarget) il cui, di chi[`IEventListener`](../ieventlistener) I messaggi di posta elettronica sono attualmente in fase di elaborazione. Ciò è particolarmente utile durante l'acquisizione e la formazione di bolle. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented) { get; } | Restituisce vero se è stato invocato preventDefault() mentre il valore dell'attributo cancellabile è vero e falso in caso contrario. |
| [DeltaMode](../../aspose.svg.dom.events/wheelevent/deltamode) { get; } | L'attributo deltaMode contiene un'indicazione delle unità di misura per i valori delta. Il valore predefinito è DOM_DELTA_PIXEL (pixel). |
| [DeltaX](../../aspose.svg.dom.events/wheelevent/deltax) { get; } | In programmi utente in cui l'azione predefinita dell'evento ruota è lo scorrimento, il valore DEVE essere la misura lungo l'asse x (in pixel, righe o pagine) da scorrere nel caso in cui l'evento non venga annullato. In caso contrario, si tratta di una misurazione specifica dell'implementazione (in pixel, linee o pagine) del movimento di un dispositivo ruota attorno all'asse x. |
| [DeltaY](../../aspose.svg.dom.events/wheelevent/deltay) { get; } | In programmi utente in cui l'azione predefinita dell'evento ruota è lo scorrimento, il valore DEVE essere la misura lungo l'asse y (in pixel, righe o pagine) da scorrere nel caso in cui l'evento non venga annullato. In caso contrario, si tratta di una misurazione specifica dell'implementazione (in pixel, linee o pagine) del movimento di un dispositivo ruota attorno all'asse y. |
| [DeltaZ](../../aspose.svg.dom.events/wheelevent/deltaz) { get; } | In programmi utente in cui l'azione predefinita dell'evento ruota è lo scorrimento, il valore DEVE essere la misura lungo l'asse z (in pixel, righe o pagine) da scorrere nel caso in cui l'evento non venga annullato. In caso contrario, si tratta di una misurazione specifica dell'implementazione (in pixel, linee o pagine) del movimento di un dispositivo ruota attorno all'asse z. |
| [Detail](../../aspose.svg.dom.events/uievent/detail) { get; } | Specifica alcune informazioni dettagliate sull'evento, a seconda del tipo di evento. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase) { get; } | Utilizzato per indicare quale fase del flusso di eventi è attualmente in fase di valutazione. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted) { get; } | L'attributo isTrusted deve restituire il valore su cui è stato inizializzato. Quando viene creato un evento, l'attributo deve essere inizializzato su false. |
| [MetaKey](../../aspose.svg.dom.events/mouseevent/metakey) { get; } | Fare riferimento all'attributo metaKey. |
| [RelatedTarget](../../aspose.svg.dom.events/mouseevent/relatedtarget) { get; } | Utilizzato per identificare un EventTarget secondario correlato a un evento dell'interfaccia utente, a seconda del tipo di evento. |
| [ScreenX](../../aspose.svg.dom.events/mouseevent/screenx) { get; } | La coordinata orizzontale in cui si è verificato l'evento rispetto all'origine del sistema di coordinate dello schermo. |
| [ScreenY](../../aspose.svg.dom.events/mouseevent/screeny) { get; } | La coordinata verticale in cui si è verificato l'evento rispetto all'origine del sistema di coordinate dello schermo. |
| [ShiftKey](../../aspose.svg.dom.events/mouseevent/shiftkey) { get; } | Fare riferimento all'attributo shiftKey. |
| [Target](../../aspose.svg.dom.events/event/target) { get; } | Usato per indicare il[`IEventTarget`](../ieventtarget) a cui l'evento è stato originariamente inviato. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp) { get; } | Utilizzato per specificare l'ora (in millisecondi rispetto all'epoca) in cui è stato creato l'evento. A causa del fatto che alcuni sistemi potrebbero non fornire queste informazioni, il valore di timeStamp potrebbe non essere disponibile per tutti gli eventi. Quando non disponibile , verrà restituito un valore di 0. Esempi di epoch time sono l'ora di inizio del sistema o 0:0:0 UTC 1 gennaio 1970. |
| [Type](../../aspose.svg.dom.events/event/type) { get; } | Il nome dell'evento (senza distinzione tra maiuscole e minuscole). Il nome deve essere un nome XML. |
| [View](../../aspose.svg.dom.events/uievent/view) { get; } | L'attributo view identifica la finestra da cui è stato generato l'evento. Il valore non inizializzato di questo attributo DEVE essere null. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent)(string, bool, bool) | Il[`InitEvent`](../event/initevent) viene utilizzato per inizializzare il valore di an[`Event`](../event) creato tramite il [`IDocumentEvent`](../idocumentevent) interfaccia. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault)() | Se un evento è annullabile, il[`PreventDefault`](../event/preventdefault) viene utilizzato per indicare che l'evento deve essere annullato, significa che qualsiasi azione predefinita normalmente intrapresa dall'implementazione a seguito dell'evento non si verificherà. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation)() | Invocare questo metodo impedisce all'evento di raggiungere qualsiasi listener di eventi registrato dopo quello corrente e quando inviato in un albero impedisce anche all'evento di raggiungere qualsiasi altro oggetto. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation)() | Il[`StopPropagation`](../event/stoppropagation) viene utilizzato per impedire l'ulteriore propagazione di un evento durante il flusso di eventi. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DOM_DELTA_LINE](../../aspose.svg.dom.events/wheelevent/dom_delta_line) | Le unità di misura per il delta DEVONO essere singole righe di testo. Questo è il caso di molti controlli modulo. |
| const [DOM_DELTA_PAGE](../../aspose.svg.dom.events/wheelevent/dom_delta_page) | Le unità di misura del delta DEVONO essere le pagine, definite sia come schermo singolo che come pagina delimitata. |
| const [DOM_DELTA_PIXEL](../../aspose.svg.dom.events/wheelevent/dom_delta_pixel) | Le unità di misura per il delta DEVONO essere pixel. Questo è il caso più tipico nella maggior parte dei sistemi operativi e delle configurazioni di implementazione. |

### Guarda anche

* class [MouseEvent](../mouseevent)
* spazio dei nomi [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events)
* assemblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->