---
title: "ErrorEvent Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Events.ErrorEvent Klasse. Das ErrorEvent liefert kontextbezogene Informationen über einen Fehler, der zur Laufzeit aufgetreten ist."
type: docs
weight: 2910
url: /de/net/aspose.svg.dom.events/errorevent/
---
## ErrorEvent class

Das `ErrorEvent` liefert kontextbezogene Informationen über einen Fehler, der zur Laufzeit aufgetreten ist.

```csharp
public class ErrorEvent : Event
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(*Exception*) | Initialisiert eine neue Instanz der `ErrorEvent` Klasse. |
| [ErrorEvent](errorevent/#constructor)(*IDictionary&lt;string, object&gt;*) | Initialisiert eine neue Instanz der `ErrorEvent` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Wird verwendet, um anzugeben, ob ein Ereignis ein Bubbling-Ereignis ist oder nicht. Wenn das Ereignis bubblingfähig ist, ist der Wert true, andernfalls false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann oder nicht. Wenn die Standardaktion verhindert werden kann, ist der Wert true, andernfalls false. |
| [ColNo](../../aspose.svg.dom.events/errorevent/colno/) { get; } | Das colno-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Beim Erstellen des Objekts muss dieses Attribut auf 0 initialisiert werden. Es stellt die Spaltennummer dar, in der der Fehler im Skript aufgetreten ist. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, dessen [`IEventListener`](../ieventlistener/) gerade verarbeitet werden. Dies ist besonders nützlich während des Capturing und Bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Gibt true zurück, wenn preventDefault() aufgerufen wurde, während das cancelable-Attribut true ist, andernfalls false. |
| [Error](../../aspose.svg.dom.events/errorevent/error/) { get; } | Das error-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Beim Erstellen des Objekts muss dieses Attribut auf null initialisiert werden. Bei Bedarf wird es auf das Objekt gesetzt, das den Fehler darstellt (z. B. das Ausnahmeobjekt im Fall einer nicht abgefangenen DOM-Ausnahme). |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Wird verwendet, um anzugeben, welche Phase des Ereignisflusses gerade ausgewertet wird. |
| [FileName](../../aspose.svg.dom.events/errorevent/filename/) { get; } | Das filename-Attribut muss den Wert zurückgeben, auf den es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut auf die leere Zeichenkette initialisiert werden. Es stellt die absolute URL des Skripts dar, in dem der Fehler ursprünglich aufgetreten ist. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Das isTrusted-Attribut muss den Wert zurückgeben, auf den es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf false initialisiert werden. |
| [LineNo](../../aspose.svg.dom.events/errorevent/lineno/) { get; } | Das lineno-Attribut muss den Wert zurückgeben, auf den es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut auf 0 initialisiert werden. Es stellt die Zeilennummer dar, in der der Fehler im Skript aufgetreten ist. |
| [Message](../../aspose.svg.dom.events/errorevent/message/) { get; } | Das message-Attribut muss den Wert zurückgeben, auf den es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut auf die leere Zeichenkette initialisiert werden. Es stellt die Fehlermeldung dar. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, an das das Ereignis ursprünglich gesendet wurde. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Wird verwendet, um die Zeit (in Millisekunden relativ zur Epoche) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Information möglicherweise nicht bereitstellen, kann der Wert von timeStamp für nicht alle Ereignisse verfügbar sein. Wenn er nicht verfügbar ist, wird ein Wert von 0 zurückgegeben. Beispiele für Epoch-Zeit sind der Systemstart oder 0:0:0 UTC, 1. Januar 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Der Name des Ereignisses (Groß-/Kleinschreibung wird ignoriert). Der Name muss ein XML-Name sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Die Methode [`InitEvent`](../event/initevent/) wird verwendet, um den Wert eines über die Schnittstelle [`IDocumentEvent`](../idocumentevent/) erstellten [`Event`](../event/) zu initialisieren. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Ist ein Ereignis abbrechbar, wird die Methode [`PreventDefault`](../event/preventdefault/) verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, sodass jede standardmäßige Aktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt würde, nicht stattfindet. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Der Aufruf dieser Methode verhindert, dass das Ereignis an nach dem aktuellen registrierte Ereignislistener gelangt, und wenn es in einem Baum verteilt wird, verhindert sie zudem, dass das Ereignis andere Objekte erreicht. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Die Methode [`StopPropagation`](../event/stoppropagation/) wird verwendet, um die weitere Weiterleitung eines Ereignisses während des Ereignisflusses zu verhindern. |

### Siehe auch

* class [Event](../event/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
