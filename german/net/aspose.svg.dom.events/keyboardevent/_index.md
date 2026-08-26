---
title: "KeyboardEvent Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Events.KeyboardEvent Klasse. Das KeyboardEvent-Interface liefert spezifische Kontextinformationen, die mit Tastaturgeräten verbunden sind. Jedes Tastaturereignis verweist über einen Wert auf eine Taste. Tastaturereignisse werden üblicherweise an das Element gerichtet, das den Fokus hat."
type: docs
weight: 2980
url: /de/net/aspose.svg.dom.events/keyboardevent/
---
## KeyboardEvent class

Das KeyboardEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Tastaturgeräten verbunden sind. Jedes Tastaturereignis verweist über einen Wert auf eine Taste. Tastaturereignisse richten sich in der Regel an das Element, das den Fokus hat.

```csharp
public class KeyboardEvent : UIEvent
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(*string*) | Initialisiert eine neue Instanz der `KeyboardEvent`-Klasse. |
| [KeyboardEvent](keyboardevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Initialisiert eine neue Instanz der `KeyboardEvent`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/keyboardevent/altkey/) { get; } | true, wenn die Alt‑ (alternativ) (oder „Option“)-Taste aktiv war. Der nicht initialisierte Wert dieses Attributs MUSS false sein. |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Wird verwendet, um anzugeben, ob ein Ereignis ein Bubbling-Ereignis ist oder nicht. Wenn das Ereignis bubblingfähig ist, ist der Wert true, andernfalls false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann oder nicht. Wenn die Standardaktion verhindert werden kann, ist der Wert true, andernfalls false. |
| [Code](../../aspose.svg.dom.events/keyboardevent/code/) { get; } | Der Code enthält eine Zeichenkette, die die physische Taste identifiziert, die gedrückt wird. Der Wert wird nicht vom aktuellen Tastaturlayout oder dem Modifizierungszustand beeinflusst, sodass eine bestimmte Taste stets denselben Wert zurückgibt. |
| [CtrlKey](../../aspose.svg.dom.events/keyboardevent/ctrlkey/) { get; } | true, wenn die Strg‑ (control)‑Taste aktiv war. Der nicht initialisierte Wert dieses Attributs MUSS false sein. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, dessen [`IEventListener`](../ieventlistener/) gerade verarbeitet werden. Dies ist besonders nützlich während des Capturing und Bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Gibt true zurück, wenn preventDefault() aufgerufen wurde, während das cancelable-Attribut true ist, andernfalls false. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Gibt einige Detailinformationen über das Ereignis an, abhängig vom Ereignistyp. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Wird verwendet, um anzugeben, welche Phase des Ereignisflusses gerade ausgewertet wird. |
| [IsComposing](../../aspose.svg.dom.events/keyboardevent/iscomposing/) { get; } | true, wenn das Tastaturereignis im Rahmen einer Kompositionssitzung auftritt, d. h. nach einem compositionstart‑Ereignis und vor dem entsprechenden compositionend‑Ereignis. Der nicht initialisierte Wert dieses Attributs MUSS false sein. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Das isTrusted-Attribut muss den Wert zurückgeben, auf den es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf false initialisiert werden. |
| [Key](../../aspose.svg.dom.events/keyboardevent/key/) { get; } | Der Schlüssel enthält den Tastwert der gedrückten Taste. Wenn der Wert eine druckbare Darstellung hat, MUSS er eine nicht leere Unicode‑Zeichenkette sein, die dem in dieser Spezifikation definierten Algorithmus zur Bestimmung des Tastwerts entspricht. Wenn der Wert eine Steuerungstaste ohne druckbare Darstellung ist, MUSS er einer der im Schlüsselwert‑Set definierten Tastwerte sein, wie durch den Algorithmus zur Bestimmung des Tastwerts ermittelt. Implementierungen, die eine Taste nicht identifizieren können, MÜSSEN den Tastwert Unidentified verwenden. |
| [Location](../../aspose.svg.dom.events/keyboardevent/location/) { get; } | Das Attribut location enthält einen Hinweis auf die logische Position der Taste auf dem Gerät. |
| [MetaKey](../../aspose.svg.dom.events/keyboardevent/metakey/) { get; } | true, wenn die Meta‑Taste (Meta) aktiv war. |
| [Repeat](../../aspose.svg.dom.events/keyboardevent/repeat/) { get; } | true, wenn die Taste über einen längeren Zeitraum gedrückt wurde. Das Gedrückthalten einer Taste MUSS dazu führen, dass die Ereignisse keydown, beforeinput, input in dieser Reihenfolge wiederholt werden, mit einer Rate, die durch die Systemkonfiguration bestimmt wird. Bei mobilen Geräten mit Langdruck‑Verhalten MUSS das erste Tastaturereignis mit dem Attribut repeat = true als Hinweis auf einen Langdruck dienen. Die Zeitdauer, die die Taste gedrückt gehalten werden MUSS, um mit dem Wiederholen zu beginnen, ist konfigurationsabhängig. |
| [ShiftKey](../../aspose.svg.dom.events/keyboardevent/shiftkey/) { get; } | true, wenn die Shift‑Taste (Shift) aktiv war. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, an das das Ereignis ursprünglich gesendet wurde. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Wird verwendet, um die Zeit (in Millisekunden relativ zur Epoche) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Information möglicherweise nicht bereitstellen, kann der Wert von timeStamp für nicht alle Ereignisse verfügbar sein. Wenn er nicht verfügbar ist, wird ein Wert von 0 zurückgegeben. Beispiele für Epoch-Zeit sind der Systemstart oder 0:0:0 UTC, 1. Januar 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Der Name des Ereignisses (Groß-/Kleinschreibung wird ignoriert). Der Name muss ein XML-Name sein. |
| [View](../../aspose.svg.dom.events/uievent/view/) { get; } | Das Attribut view identifiziert das Fenster, von dem das Ereignis erzeugt wurde. Der nicht initialisierte Wert dieses Attributs MUSS null sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Die Methode [`InitEvent`](../event/initevent/) wird verwendet, um den Wert eines über die Schnittstelle [`IDocumentEvent`](../idocumentevent/) erstellten [`Event`](../event/) zu initialisieren. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Ist ein Ereignis abbrechbar, wird die Methode [`PreventDefault`](../event/preventdefault/) verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, sodass jede standardmäßige Aktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt würde, nicht stattfindet. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Der Aufruf dieser Methode verhindert, dass das Ereignis an nach dem aktuellen registrierte Ereignislistener gelangt, und wenn es in einem Baum verteilt wird, verhindert sie zudem, dass das Ereignis andere Objekte erreicht. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Die Methode [`StopPropagation`](../event/stoppropagation/) wird verwendet, um die weitere Weiterleitung eines Ereignisses während des Ereignisflusses zu verhindern. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_left/) | Die aktivierte Taste stammt aus der linken Tastposition (wenn es mehr als einen möglichen Ort für diese Taste gibt). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_numpad/) | Die Tastaktivierung stammt vom Ziffernblock oder von einer virtuellen Taste, die dem Ziffernblock entspricht (wenn es mehr als einen möglichen Ort für diese Taste gibt). Hinweis: Die NumLock‑Taste sollte immer mit dem Standort DOM_KEY_LOCATION_STANDARD kodiert werden. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_right/) | Die Tastaktivierung stammt aus der rechten Tastposition (wenn es mehr als einen möglichen Ort für diese Taste gibt). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_standard/) | Die Tastaktivierung DARF NICHT als linke oder rechte Version der Taste unterschieden werden und (außer bei der NumLock‑Taste) stammt nicht vom Ziffernblock (oder von einer virtuellen Taste, die dem Ziffernblock entspricht). |

### Siehe auch

* class [UIEvent](../uievent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
