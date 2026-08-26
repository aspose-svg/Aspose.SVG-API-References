---
title: "InputEvent‑Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Events.InputEvent‑Klasse. Eingabeereignisse werden als Benachrichtigungen gesendet, wann immer das DOM aktualisiert wird."
type: docs
weight: 2970
url: /de/net/aspose.svg.dom.events/inputevent/
---
## InputEvent class

Eingabeereignisse werden als Benachrichtigungen gesendet, wann immer das DOM aktualisiert wird.

```csharp
public class InputEvent : UIEvent
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [InputEvent](inputevent/#constructor)(*string*) | Initialisiert eine neue Instanz der `InputEvent`‑Klasse. |
| [InputEvent](inputevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Initialisiert eine neue Instanz der `InputEvent`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Wird verwendet, um anzugeben, ob ein Ereignis ein Bubbling-Ereignis ist oder nicht. Wenn das Ereignis bubblingfähig ist, ist der Wert true, andernfalls false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann oder nicht. Wenn die Standardaktion verhindert werden kann, ist der Wert true, andernfalls false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, dessen [`IEventListener`](../ieventlistener/) gerade verarbeitet werden. Dies ist besonders nützlich während des Capturing und Bubbling. |
| [Data](../../aspose.svg.dom.events/inputevent/data/) { get; } | Die Daten enthalten den Wert der von einer Eingabemethode erzeugten Zeichen. Dies KANN ein einzelnes Unicode‑Zeichen oder eine nicht leere Sequenz von Unicode‑Zeichen sein [Unicode]. Zeichen SOLLTEN gemäß der Unicode‑Normalisierungsform NFC, definiert in [UAX15], normalisiert werden. Dieses Attribut KANN die leere Zeichenkette enthalten. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Gibt true zurück, wenn preventDefault() aufgerufen wurde, während das cancelable-Attribut true ist, andernfalls false. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Gibt einige Detailinformationen über das Ereignis an, abhängig vom Ereignistyp. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Wird verwendet, um anzugeben, welche Phase des Ereignisflusses gerade ausgewertet wird. |
| [IsComposing](../../aspose.svg.dom.events/inputevent/iscomposing/) { get; } | true, wenn das Eingabeereignis Teil einer Kompositionssitzung ist, d. h. nach einem compositionstart‑Ereignis und vor dem entsprechenden compositionend‑Ereignis. Der nicht initialisierte Wert dieses Attributs MUSS false sein. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Das isTrusted-Attribut muss den Wert zurückgeben, auf den es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf false initialisiert werden. |
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

### Siehe auch

* class [UIEvent](../uievent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
