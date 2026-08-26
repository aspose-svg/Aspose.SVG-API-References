---
title: "TimeEvent Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Events.TimeEvent Klasse. Die TimeEvent‑Schnittstelle liefert spezifische Kontextinformationen, die mit Zeit‑Ereignissen verbunden sind. Die verschiedenen Ereignistypen, die auftreten können, sind beginEvent, endEvent und repeatEvent."
type: docs
weight: 3720
url: /de/net/aspose.svg.events/timeevent/
---
## TimeEvent class

The TimeEvent interface provides specific contextual information associated with Time events.The different types of events that can occur are: beginEvent, endEvent and repeatEvent.

```csharp
public class TimeEvent : Event
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Wird verwendet, um anzugeben, ob ein Ereignis ein Bubbling-Ereignis ist oder nicht. Wenn das Ereignis bubblingfähig ist, ist der Wert true, andernfalls false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann oder nicht. Wenn die Standardaktion verhindert werden kann, ist der Wert true, andernfalls false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Wird verwendet, um das [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) anzugeben, dessen [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)s gerade verarbeitet werden. Dies ist besonders nützlich während des Capturing und Bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Gibt true zurück, wenn preventDefault() aufgerufen wurde, während das cancelable-Attribut true ist, andernfalls false. |
| [Detail](../../aspose.svg.events/timeevent/detail/) { get; } | Gibt einige Detailinformationen über das Ereignis an, abhängig vom Typ des Ereignisses. Für diesen Ereignistyp gibt sie die Wiederholungszahl für die Animation an. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Wird verwendet, um anzugeben, welche Phase des Ereignisflusses gerade ausgewertet wird. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Das isTrusted-Attribut muss den Wert zurückgeben, auf den es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf false initialisiert werden. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Wird verwendet, um das [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) anzugeben, an das das Ereignis ursprünglich gesendet wurde. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Wird verwendet, um die Zeit (in Millisekunden relativ zur Epoche) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Information möglicherweise nicht bereitstellen, kann der Wert von timeStamp für nicht alle Ereignisse verfügbar sein. Wenn er nicht verfügbar ist, wird ein Wert von 0 zurückgegeben. Beispiele für Epoch-Zeit sind der Systemstart oder 0:0:0 UTC, 1. Januar 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Der Name des Ereignisses (Groß-/Kleinschreibung wird ignoriert). Der Name muss ein XML-Name sein. |
| [View](../../aspose.svg.events/timeevent/view/) { get; } | Das view‑Attribut identifiziert die AbstractView [DOM2VIEWS], von der das Ereignis erzeugt wurde. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Die Methode [`InitEvent`](../../aspose.svg.dom.events/event/initevent/) wird verwendet, um den Wert eines über die [`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/) Schnittstelle erstellten [`Event`](../../aspose.svg.dom.events/event/) zu initialisieren. |
| [InitTimeEvent](../../aspose.svg.events/timeevent/inittimeevent/)(*string, [IAbstractView](../../aspose.svg.dom.views/iabstractview/), long*) | Die Methode initTimeEvent wird verwendet, um den Wert eines über die DocumentEvent‑Schnittstelle erstellten TimeEvent zu initialisieren. Diese Methode darf nur aufgerufen werden, bevor das TimeEvent über die dispatchEvent‑Methode gesendet wurde, kann jedoch bei Bedarf während dieser Phase mehrfach aufgerufen werden. Wird sie mehrfach aufgerufen, hat der letzte Aufruf Vorrang. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Wenn ein Ereignis abbrechbar ist, wird die Methode [`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/) verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, sodass jede standardmäßige Aktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht erfolgt. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Der Aufruf dieser Methode verhindert, dass das Ereignis an nach dem aktuellen registrierte Ereignislistener gelangt, und wenn es in einem Baum verteilt wird, verhindert sie zudem, dass das Ereignis andere Objekte erreicht. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Die Methode [`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/) wird verwendet, um die weitere Weiterleitung eines Ereignisses während des Ereignisflusses zu verhindern. |

### Siehe auch

* class [Event](../../aspose.svg.dom.events/event/)
* namespace [Aspose.Svg.Events](../../aspose.svg.events/)
* assembly [Aspose.SVG](../../)
