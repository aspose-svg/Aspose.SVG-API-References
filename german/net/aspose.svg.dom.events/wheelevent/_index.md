---
title: "WheelEvent‑Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Events.WheelEvent‑Klasse. Die WheelEvent‑Schnittstelle liefert spezifische Kontextinformationen, die mit Rad‑Ereignissen verbunden sind. Um eine Instanz der WheelEvent‑Schnittstelle zu erstellen, verwenden Sie den WheelEvent‑Konstruktor und übergeben ein optionales WheelEventInit‑Dictionary."
type: docs
weight: 3010
url: /de/net/aspose.svg.dom.events/wheelevent/
---
## WheelEvent class

Das WheelEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Radereignissen verbunden sind. Um eine Instanz des WheelEvent-Interface zu erstellen, verwenden Sie den WheelEvent-Konstruktor und übergeben ein optionales WheelEventInit-Wörterbuch.

```csharp
public class WheelEvent : MouseEvent
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(*string*) | Initialisiert eine neue Instanz der `WheelEvent`‑Klasse. |
| [WheelEvent](wheelevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Initialisiert eine neue Instanz der `WheelEvent`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/mouseevent/altkey/) { get; } | Beziehen Sie sich auf das Attribut altKey. |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Wird verwendet, um anzugeben, ob ein Ereignis ein Bubbling-Ereignis ist oder nicht. Wenn das Ereignis bubblingfähig ist, ist der Wert true, andernfalls false. |
| [Button](../../aspose.svg.dom.events/mouseevent/button/) { get; } | Während Mausereignissen, die durch das Drücken oder Loslassen einer Maustaste verursacht werden, MUSS button verwendet werden, um anzugeben, welche Zeigegerät‑Taste den Zustand geändert hat. |
| [Buttons](../../aspose.svg.dom.events/mouseevent/buttons/) { get; } | Während aller Mausereignisse MUSS buttons verwendet werden, um anzugeben, welche Kombination von Maustasten derzeit gedrückt ist, ausgedrückt als Bitmaske. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann oder nicht. Wenn die Standardaktion verhindert werden kann, ist der Wert true, andernfalls false. |
| [ClientX](../../aspose.svg.dom.events/mouseevent/clientx/) { get; } | Die horizontale Koordinate, bei der das Ereignis relativ zum mit dem Ereignis verbundenen Ansichtsfenster auftrat. |
| [ClientY](../../aspose.svg.dom.events/mouseevent/clienty/) { get; } | Die vertikale Koordinate, bei der das Ereignis relativ zum mit dem Ereignis verbundenen Ansichtsfenster auftrat. |
| [CtrlKey](../../aspose.svg.dom.events/mouseevent/ctrlkey/) { get; } | Beziehen Sie sich auf das Attribut ctrlKey. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, dessen [`IEventListener`](../ieventlistener/) gerade verarbeitet werden. Dies ist besonders nützlich während des Capturing und Bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Gibt true zurück, wenn preventDefault() aufgerufen wurde, während das cancelable-Attribut true ist, andernfalls false. |
| [DeltaMode](../../aspose.svg.dom.events/wheelevent/deltamode/) { get; } | Das Attribut deltaMode enthält einen Hinweis auf die Maßeinheiten für die Delta‑Werte. Der Standardwert ist DOM_DELTA_PIXEL (Pixel). |
| [DeltaX](../../aspose.svg.dom.events/wheelevent/deltax/) { get; } | In Benutzeragenten, bei denen die Standardaktion des Wheel-Events das Scrollen ist, MUSS der Wert die Messung entlang der x-Achse (in Pixeln, Zeilen oder Seiten) sein, die gescrollt wird, falls das Ereignis nicht abgebrochen wird. Andernfalls handelt es sich um eine implementierungsspezifische Messung (in Pixeln, Zeilen oder Seiten) der Bewegung eines Wheel-Geräts um die x-Achse. |
| [DeltaY](../../aspose.svg.dom.events/wheelevent/deltay/) { get; } | In Benutzeragenten, bei denen die Standardaktion des Wheel-Events das Scrollen ist, MUSS der Wert die Messung entlang der y-Achse (in Pixeln, Zeilen oder Seiten) sein, die gescrollt wird, falls das Ereignis nicht abgebrochen wird. Andernfalls handelt es sich um eine implementierungsspezifische Messung (in Pixeln, Zeilen oder Seiten) der Bewegung eines Wheel-Geräts um die y-Achse. |
| [DeltaZ](../../aspose.svg.dom.events/wheelevent/deltaz/) { get; } | In Benutzeragenten, bei denen die Standardaktion des Wheel-Events das Scrollen ist, MUSS der Wert die Messung entlang der z-Achse (in Pixeln, Zeilen oder Seiten) sein, die gescrollt wird, falls das Ereignis nicht abgebrochen wird. Andernfalls handelt es sich um eine implementierungsspezifische Messung (in Pixeln, Zeilen oder Seiten) der Bewegung eines Wheel-Geräts um die z-Achse. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Gibt einige Detailinformationen über das Ereignis an, abhängig vom Ereignistyp. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Wird verwendet, um anzugeben, welche Phase des Ereignisflusses gerade ausgewertet wird. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Das isTrusted-Attribut muss den Wert zurückgeben, auf den es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf false initialisiert werden. |
| [MetaKey](../../aspose.svg.dom.events/mouseevent/metakey/) { get; } | Beziehen Sie sich auf das Attribut metaKey. |
| [RelatedTarget](../../aspose.svg.dom.events/mouseevent/relatedtarget/) { get; } | Wird verwendet, um ein sekundäres EventTarget zu identifizieren, das mit einem UI-Ereignis in Zusammenhang steht, abhängig vom Ereignistyp. |
| [ScreenX](../../aspose.svg.dom.events/mouseevent/screenx/) { get; } | Die horizontale Koordinate, bei der das Ereignis relativ zum Ursprung des Bildschirmkoordinatensystems auftrat. |
| [ScreenY](../../aspose.svg.dom.events/mouseevent/screeny/) { get; } | Die vertikale Koordinate, bei der das Ereignis relativ zum Ursprung des Bildschirmkoordinatensystems auftrat. |
| [ShiftKey](../../aspose.svg.dom.events/mouseevent/shiftkey/) { get; } | Beziehen Sie sich auf das Attribut shiftKey. |
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
| const [DOM_DELTA_LINE](../../aspose.svg.dom.events/wheelevent/dom_delta_line/) | Die Maßeinheiten für das Delta MÜSSEN einzelne Textzeilen sein. Dies ist bei vielen Formularelementen der Fall. |
| const [DOM_DELTA_PAGE](../../aspose.svg.dom.events/wheelevent/dom_delta_page/) | Die Maßeinheiten für das Delta MÜSSEN Seiten sein, entweder definiert als ein einzelner Bildschirm oder als eine abgegrenzte Seite. |
| const [DOM_DELTA_PIXEL](../../aspose.svg.dom.events/wheelevent/dom_delta_pixel/) | Die Maßeinheiten für das Delta MÜSSEN Pixel sein. Dies ist der häufigste Fall in den meisten Betriebssystem‑ und Implementierungskonfigurationen. |

### Siehe auch

* class [MouseEvent](../mouseevent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
