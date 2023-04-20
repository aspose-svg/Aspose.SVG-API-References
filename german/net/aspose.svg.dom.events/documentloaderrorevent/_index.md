---
title: Class DocumentLoadErrorEvent
second_title: Aspose.SVG für .NET-API-Referenz
description: Aspose.Svg.Dom.Events.DocumentLoadErrorEvent klas. DieDocumentLoadErrorEvent tritt auf wenn die angeforderte Ressource nicht verfügbar ist.
type: docs
weight: 900
url: /de/net/aspose.svg.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

Die`DocumentLoadErrorEvent` tritt auf, wenn die angeforderte Ressource nicht verfügbar ist.

```csharp
public class DocumentLoadErrorEvent : ErrorEvent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Wird verwendet, um anzugeben, ob ein Ereignis ein Blasenereignis ist oder nicht. Wenn das Ereignis sprudeln kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann oder nicht. Wenn die Standardaktion verhindert werden kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [ColNo](../../aspose.svg.dom.events/errorevent/colno/) { get; } | Das colno-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut auf Null initialisiert werden. Es stellt die Spaltennummer dar, in der der Fehler im Skript aufgetreten ist. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Wird verwendet, um die anzuzeigen[`IEventTarget`](../ieventtarget/) wessen[`IEventListener`](../ieventlistener/) s werden gerade verarbeitet. Dies ist besonders nützlich beim Erfassen und Bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Gibt „true“ zurück, wenn preventDefault() aufgerufen wurde, während der Wert des abbrechbaren Attributs „true“ ist, andernfalls „false“. |
| [Error](../../aspose.svg.dom.events/errorevent/error/) { get; } | Das Fehlerattribut muss den Wert zurückgeben, auf den es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut auf null initialisiert werden. Gegebenenfalls wird es auf das Objekt gesetzt, das den Fehler darstellt (z. B. das Ausnahmeobjekt im Fall einer nicht abgefangenen DOM-Ausnahme). |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Wird verwendet, um anzugeben, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [FileName](../../aspose.svg.dom.events/errorevent/filename/) { get; } | Das filename-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut mit der leeren Zeichenfolge initialisiert werden. Es stellt die absolute URL des Skripts dar, in dem der Fehler ursprünglich aufgetreten ist. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Das isTrusted-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf „false“ initialisiert werden. |
| [LineNo](../../aspose.svg.dom.events/errorevent/lineno/) { get; } | Das lineno-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut auf Null initialisiert werden. Es stellt die Zeilennummer dar, in der der Fehler im Skript aufgetreten ist. |
| [Message](../../aspose.svg.dom.events/errorevent/message/) { get; } | Das Nachrichtenattribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut mit der leeren Zeichenfolge initialisiert werden. Es stellt die Fehlermeldung dar. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Wird verwendet, um die anzuzeigen[`IEventTarget`](../ieventtarget/) an die das Ereignis ursprünglich gesendet wurde. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Wird verwendet, um die Zeit (in Millisekunden relativ zur Epoche) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Informationen möglicherweise nicht bereitstellen, ist der Wert von timeStamp möglicherweise nicht für alle Ereignisse verfügbar. Wenn nicht verfügbar , wird ein Wert von 0 zurückgegeben. Beispiele für Epochenzeit sind die Zeit des Systemstarts oder 0:0:0 UTC 1. Januar 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Der Name des Ereignisses (Groß-/Kleinschreibung wird nicht beachtet). Der Name muss ein XML-Name sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | Die[`InitEvent`](../event/initevent/) -Methode wird verwendet, um den Wert von an zu initialisieren[`Event`](../event/) erstellt durch the [`IDocumentEvent`](../idocumentevent/) Schnittstelle. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Wenn eine Veranstaltung stornierbar ist, wird die[`PreventDefault`](../event/preventdefault/) -Methode wird verwendet, um anzugeben, dass das Ereignis abgebrochen werden soll, , was bedeutet, dass eine Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht ausgeführt wird. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Das Aufrufen dieser Methode verhindert, dass das Ereignis alle Ereignis-Listener erreicht, die nach dem aktuellen registriert sind, und wenn es in einem Baum gesendet wird, verhindert es auch, dass das Ereignis andere Objekte erreicht. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Die[`StopPropagation`](../event/stoppropagation/) -Methode verwendet wird, verhindert die weitere Ausbreitung eines Ereignisses während des Ereignisflusses. |

### Siehe auch

* class [ErrorEvent](../errorevent/)
* namensraum [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* Montage [Aspose.SVG](../../)


