---
title: Event
second_title: Aspose.SVG für .NET-API-Referenz
description: DieEvent./event wird verwendet um dem Handler der das Ereignis verarbeitet Kontextinformationen zu einem Ereignis bereitzustellen.
type: docs
weight: 920
url: /de/net/aspose.svg.dom.events/event/
---
## Event class

Die[`Event`](../event) wird verwendet, um dem Handler, der das Ereignis verarbeitet, Kontextinformationen zu einem Ereignis bereitzustellen.

```csharp
public class Event : DOMObject
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Event](event#constructor)(string) | Initialisiert eine neue Instanz von[`Event`](../event) Klasse. |
| [Event](event#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initialisiert eine neue Instanz von[`Event`](../event) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles) { get; } | Wird verwendet, um anzugeben, ob ein Ereignis ein Blasenereignis ist oder nicht. Wenn das Ereignis sprudeln kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable) { get; } | Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann oder nicht. Wenn die Standardaktion verhindert werden kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget) { get; } | Wird verwendet, um die anzuzeigen[`IEventTarget`](../ieventtarget) Deren[`IEventListener`](../ieventlistener) s werden gerade verarbeitet. Dies ist besonders nützlich beim Erfassen und Bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented) { get; } | Gibt „true“ zurück, wenn preventDefault() aufgerufen wurde, während der Wert des abbrechbaren Attributs „true“ ist, andernfalls „false“. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase) { get; } | Wird verwendet, um anzugeben, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted) { get; } | Das isTrusted-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf „false“ initialisiert werden. |
| [Target](../../aspose.svg.dom.events/event/target) { get; } | Wird verwendet, um die anzuzeigen[`IEventTarget`](../ieventtarget) an die das Ereignis ursprünglich gesendet wurde. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp) { get; } | Wird verwendet, um die Zeit (in Millisekunden relativ zur Epoche) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Informationen möglicherweise nicht bereitstellen, ist der Wert von timeStamp möglicherweise nicht für alle Ereignisse verfügbar. Wenn nicht verfügbar , wird ein Wert von 0 zurückgegeben. Beispiele für Epochenzeit sind die Zeit des Systemstarts oder 0:0:0 UTC 1. Januar 1970. |
| [Type](../../aspose.svg.dom.events/event/type) { get; } | Der Name des Ereignisses (Groß-/Kleinschreibung wird nicht beachtet). Der Name muss ein XML-Name sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent)(string, bool, bool) | Die[`InitEvent`](./initevent) -Methode wird verwendet, um den Wert von an zu initialisieren[`Event`](../event) erstellt durch the [`IDocumentEvent`](../idocumentevent) Schnittstelle. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault)() | Wenn eine Veranstaltung stornierbar ist, wird die[`PreventDefault`](./preventdefault) -Methode wird verwendet, um anzugeben, dass das Ereignis abgebrochen werden soll, , was bedeutet, dass eine Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht ausgeführt wird. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation)() | Das Aufrufen dieser Methode verhindert, dass das Ereignis alle Ereignis-Listener erreicht, die nach dem aktuellen registriert sind, und wenn es in einem Baum gesendet wird, verhindert es auch, dass das Ereignis andere Objekte erreicht. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation)() | Die[`StopPropagation`](./stoppropagation) -Methode verwendet wird, verhindert die weitere Ausbreitung eines Ereignisses während des Ereignisflusses. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [AtTargetPhase](../../aspose.svg.dom.events/event/attargetphase) | Die aktuelle Ereignisphase ist die Erfassungsphase. |
| const [BubblingPhase](../../aspose.svg.dom.events/event/bubblingphase) | Die aktuelle Ereignisphase ist die Sprudelphase. |
| const [CapturingPhase](../../aspose.svg.dom.events/event/capturingphase) | Das Ereignis wird gerade am Target ausgewertet[`IEventTarget`](../ieventtarget) . |
| const [NonePhase](../../aspose.svg.dom.events/event/nonephase) | Derzeit nicht versendete Ereignisse befinden sich in dieser Phase. |

### Bemerkungen

Ein Objekt, das die implementiert[`Event`](../event) wird im Allgemeinen als erster Parameter an einen Event-Handler übergeben. Spezifischere Kontextinformationen werden an Event-Handler übergeben, indem zusätzliche Schnittstellen von abgeleitet werden[`Event`](../event) die Informationen enthalten, die sich direkt auf die Art des Ereignisses beziehen, das sie begleiten. Diese abgeleiteten Schnittstellen werden auch von dem Objekt implementiert, das an den Ereignis-Listener übergeben wird.

### Siehe auch

* class [DOMObject](../../aspose.svg.dom/domobject)
* namensraum [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events)
* Montage [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
