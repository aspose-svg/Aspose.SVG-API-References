---
title: "Event‑Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Events.Event‑Klasse. Das Event wird verwendet, um Kontextinformationen zu einem Ereignis dem Handler bereitzustellen, der das Ereignis verarbeitet."
type: docs
weight: 2920
url: /de/net/aspose.svg.dom.events/event/
---
## Event class

Das `Event` wird verwendet, um Kontextinformationen zu einem Ereignis dem Handler bereitzustellen, der das Ereignis verarbeitet.

```csharp
public class Event : DOMObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Event](event/#constructor)(*string*) | Initialisiert eine neue Instanz der `Event`‑Klasse. |
| [Event](event/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Initialisiert eine neue Instanz der `Event`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Wird verwendet, um anzugeben, ob ein Ereignis ein Bubbling-Ereignis ist oder nicht. Wenn das Ereignis bubblingfähig ist, ist der Wert true, andernfalls false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann oder nicht. Wenn die Standardaktion verhindert werden kann, ist der Wert true, andernfalls false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, dessen [`IEventListener`](../ieventlistener/) gerade verarbeitet werden. Dies ist besonders nützlich während des Capturing und Bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Gibt true zurück, wenn preventDefault() aufgerufen wurde, während das cancelable-Attribut true ist, andernfalls false. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Wird verwendet, um anzugeben, welche Phase des Ereignisflusses gerade ausgewertet wird. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Das isTrusted-Attribut muss den Wert zurückgeben, auf den es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf false initialisiert werden. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, an das das Ereignis ursprünglich gesendet wurde. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Wird verwendet, um die Zeit (in Millisekunden relativ zur Epoche) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Information möglicherweise nicht bereitstellen, kann der Wert von timeStamp für nicht alle Ereignisse verfügbar sein. Wenn er nicht verfügbar ist, wird ein Wert von 0 zurückgegeben. Beispiele für Epoch-Zeit sind der Systemstart oder 0:0:0 UTC, 1. Januar 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Der Name des Ereignisses (Groß-/Kleinschreibung wird ignoriert). Der Name muss ein XML-Name sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Die [`InitEvent`](./initevent/) Methode wird verwendet, um den Wert eines `Event` zu initialisieren, das über das [`IDocumentEvent`](../idocumentevent/) Interface erstellt wurde. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Wenn ein Ereignis abbrechbar ist, wird die [`PreventDefault`](./preventdefault/) Methode verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, was bedeutet, dass jede Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht erfolgt. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Der Aufruf dieser Methode verhindert, dass das Ereignis an nach dem aktuellen registrierte Ereignislistener gelangt, und wenn es in einem Baum verteilt wird, verhindert sie zudem, dass das Ereignis andere Objekte erreicht. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Die [`StopPropagation`](./stoppropagation/) Methode wird verwendet, um die weitere Ausbreitung eines Ereignisses während des Ereignisflusses zu verhindern. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [AtTargetPhase](../../aspose.svg.dom.events/event/attargetphase/) | Die aktuelle Ereignisphase ist die Erfassungsphase. |
| const [BubblingPhase](../../aspose.svg.dom.events/event/bubblingphase/) | Die aktuelle Ereignisphase ist die Blasenphase. |
| const [CapturingPhase](../../aspose.svg.dom.events/event/capturingphase/) | Das Ereignis wird derzeit am Ziel [`IEventTarget`](../ieventtarget/) ausgewertet. |
| const [NonePhase](../../aspose.svg.dom.events/event/nonephase/) | Ereignisse, die derzeit nicht ausgelöst werden, befinden sich in dieser Phase. |

## Hinweise

Ein Objekt, das das `Event` implementiert, wird in der Regel als erster Parameter an einen Ereignishandler übergeben. Spezifischere Kontextinformationen werden an Ereignishandler übergeben, indem zusätzliche Schnittstellen von `Event` abgeleitet werden, die Informationen enthalten, die sich direkt auf den Typ des begleitenden Ereignisses beziehen. Diese abgeleiteten Schnittstellen werden ebenfalls von dem an den Ereignislistener übergebenen Objekt implementiert.

### Siehe auch

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
