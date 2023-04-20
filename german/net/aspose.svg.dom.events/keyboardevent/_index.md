---
title: Class KeyboardEvent
second_title: Aspose.SVG für .NET-API-Referenz
description: Aspose.Svg.Dom.Events.KeyboardEvent klas. Die KeyboardEventSchnittstelle stellt spezifische Kontextinformationen bereit die Tastaturgeräten zugeordnet sind. Jedes Tastaturereignis verweist mit einem Wert auf eine Taste. Tastaturereignisse werden normalerweise an das Element gerichtet das den Fokus hat.
type: docs
weight: 980
url: /de/net/aspose.svg.dom.events/keyboardevent/
---
## KeyboardEvent class

Die KeyboardEvent-Schnittstelle stellt spezifische Kontextinformationen bereit, die Tastaturgeräten zugeordnet sind. Jedes Tastaturereignis verweist mit einem Wert auf eine Taste. Tastaturereignisse werden normalerweise an das Element gerichtet, das den Fokus hat.

```csharp
public class KeyboardEvent : UIEvent
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(string) | Initialisiert eine neue Instanz von`KeyboardEvent` Klasse. |
| [KeyboardEvent](keyboardevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initialisiert eine neue Instanz von`KeyboardEvent` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/keyboardevent/altkey/) { get; } | wahr, wenn der Tastenmodifikator Alt (alternativ) (oder "Option") aktiv war. Der nicht initialisierte Wert dieses Attributs MUSS false sein. |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Wird verwendet, um anzugeben, ob ein Ereignis ein Blasenereignis ist oder nicht. Wenn das Ereignis sprudeln kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann oder nicht. Wenn die Standardaktion verhindert werden kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [Code](../../aspose.svg.dom.events/keyboardevent/code/) { get; } | Der Code enthält eine Zeichenfolge, die die gedrückte physische Taste identifiziert. Der Wert wird nicht durch das aktuelle Tastaturlayout oder den Modifikatorstatus beeinflusst, sodass eine bestimmte Taste immer denselben Wert zurückgibt. |
| [CtrlKey](../../aspose.svg.dom.events/keyboardevent/ctrlkey/) { get; } | wahr, wenn der Steuertasten-Modifikator aktiv war. Der nicht initialisierte Wert dieses Attributs MUSS falsch sein. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Wird verwendet, um die anzuzeigen[`IEventTarget`](../ieventtarget/) wessen[`IEventListener`](../ieventlistener/) s werden gerade verarbeitet. Dies ist besonders nützlich beim Erfassen und Bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Gibt „true“ zurück, wenn preventDefault() aufgerufen wurde, während der Wert des abbrechbaren Attributs „true“ ist, andernfalls „false“. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Gibt je nach Art des Ereignisses einige Detailinformationen zum Ereignis an. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Wird verwendet, um anzugeben, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [IsComposing](../../aspose.svg.dom.events/keyboardevent/iscomposing/) { get; } | wahr, wenn das Schlüsselereignis als Teil einer Zusammensetzungssitzung auftritt, dh nach einem Zusammensetzungsstartereignis und vor dem entsprechenden Zusammensetzungsendereignis. Der nicht initialisierte Wert dieses Attributs MUSS false sein. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Das isTrusted-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf „false“ initialisiert werden. |
| [Key](../../aspose.svg.dom.events/keyboardevent/key/) { get; } | Die Taste enthält den Tastenwert der gedrückten Taste. Wenn der Wert eine gedruckte Darstellung hat, MUSS es sich um eine nicht leere Unicode-Zeichenfolge handeln, die dem in dieser Spezifikation definierten Algorithmus zur Bestimmung des Schlüsselwerts entspricht. Wenn der Wert ein Kontrollschlüssel ist, der keine gedruckte Darstellung hat, MUSS er einer der Schlüsselwerte sein, die im Schlüsselwertsatz definiert sind, wie durch den Algorithmus zur Bestimmung des Schlüsselwerts bestimmt. Implementierungen, die keinen Schlüssel identifizieren können, MÜSSEN den Schlüsselwert Unidentified. verwenden. |
| [Location](../../aspose.svg.dom.events/keyboardevent/location/) { get; } | Das Standortattribut enthält einen Hinweis auf den logischen Standort des Schlüssels auf dem Gerät. |
| [MetaKey](../../aspose.svg.dom.events/keyboardevent/metakey/) { get; } | wahr, wenn der Meta-(Meta-)Tastenmodifikator aktiv war. |
| [Repeat](../../aspose.svg.dom.events/keyboardevent/repeat/) { get; } | wahr, wenn die Taste lange gedrückt wurde. Das Gedrückthalten einer Taste MUSS dazu führen, dass die Ereignisse keydown, beforeinput, input in dieser Reihenfolge mit einer von der Systemkonfiguration festgelegten Rate wiederholt werden. Für Mobilgeräte mit langem Tastendruckverhalten MUSS das erste Tastenereignis mit einem Wiederholungsattributwert von true als Hinweis auf einen langen Tastendruck dienen. Die Zeitdauer, die die Taste gedrückt werden MUSS, um mit der Wiederholung zu beginnen, ist konfigurationsabhängig. |
| [ShiftKey](../../aspose.svg.dom.events/keyboardevent/shiftkey/) { get; } | wahr, wenn der Modifikator der Umschalttaste (Shift) aktiv war. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Wird verwendet, um die anzuzeigen[`IEventTarget`](../ieventtarget/) an die das Ereignis ursprünglich gesendet wurde. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Wird verwendet, um die Zeit (in Millisekunden relativ zur Epoche) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Informationen möglicherweise nicht bereitstellen, ist der Wert von timeStamp möglicherweise nicht für alle Ereignisse verfügbar. Wenn nicht verfügbar , wird ein Wert von 0 zurückgegeben. Beispiele für Epochenzeit sind die Zeit des Systemstarts oder 0:0:0 UTC 1. Januar 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Der Name des Ereignisses (Groß-/Kleinschreibung wird nicht beachtet). Der Name muss ein XML-Name sein. |
| [View](../../aspose.svg.dom.events/uievent/view/) { get; } | Das Ansichtsattribut identifiziert das Fenster, aus dem das Ereignis generiert wurde. Der nicht initialisierte Wert dieses Attributs MUSS null sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | Die[`InitEvent`](../event/initevent/) -Methode wird verwendet, um den Wert von an zu initialisieren[`Event`](../event/) erstellt durch the [`IDocumentEvent`](../idocumentevent/) Schnittstelle. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Wenn eine Veranstaltung stornierbar ist, wird die[`PreventDefault`](../event/preventdefault/) -Methode wird verwendet, um anzugeben, dass das Ereignis abgebrochen werden soll, , was bedeutet, dass eine Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht ausgeführt wird. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Das Aufrufen dieser Methode verhindert, dass das Ereignis alle Ereignis-Listener erreicht, die nach dem aktuellen registriert sind, und wenn es in einem Baum gesendet wird, verhindert es auch, dass das Ereignis andere Objekte erreicht. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Die[`StopPropagation`](../event/stoppropagation/) -Methode verwendet wird, verhindert die weitere Ausbreitung eines Ereignisses während des Ereignisflusses. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_left/) | Der aktivierte Schlüssel stammt von der linken Schlüsselposition (wenn es mehr als eine mögliche Position für diese Taste gibt). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_numpad/) | Die Tastenaktivierung stammt von der numerischen Tastatur oder von einer virtuellen Taste, die der numerischen Tastatur entspricht (wenn es mehr als eine mögliche Position für diese Taste gibt). Beachten Sie, dass die NumLock-Taste immer mit einer Position von DOM_KEY_LOCATION_STANDARD. codiert werden sollte. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_right/) | Die Schlüsselaktivierung stammt von der richtigen Schlüsselposition (wenn es mehr als eine mögliche Position für diesen Schlüssel gibt). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_standard/) | Die Tastenaktivierung DARF NICHT als linke oder rechte Version der Taste unterschieden werden und (anders als die NumLock-Taste) nicht vom Ziffernblock stammen (oder nicht von einer virtuellen Taste stammen, die dem Ziffernblock entspricht). |

### Siehe auch

* class [UIEvent](../uievent/)
* namensraum [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* Montage [Aspose.SVG](../../)


