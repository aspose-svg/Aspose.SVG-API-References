---
title: "WheelEvent-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Events.WheelEvent-klass. WheelEvent-gränssnittet tillhandahåller specifik kontextuell information som är associerad med hjulhändelser. För att skapa en instans av WheelEvent-gränssnittet, använd WheelEvent-konstruktorn och skicka ett valfritt WheelEventInit-lexikon."
type: docs
weight: 3010
url: /sv/net/aspose.svg.dom.events/wheelevent/
---
## WheelEvent class

WheelEvent-gränssnittet tillhandahåller specifik kontextuell information som är associerad med hjulhändelser. För att skapa en instans av WheelEvent‑gränssnittet, använd WheelEvent‑konstruktorn och skicka ett valfritt WheelEventInit‑lexikon.

```csharp
public class WheelEvent : MouseEvent
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(*string*) | Initierar en ny instans av klassen `WheelEvent`. |
| [WheelEvent](wheelevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Initierar en ny instans av klassen `WheelEvent`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/mouseevent/altkey/) { get; } | Se attributet altKey. |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Används för att ange om en händelse är en bubblande händelse eller inte. Om händelsen kan bubbla är värdet true, annars är värdet false. |
| [Button](../../aspose.svg.dom.events/mouseevent/button/) { get; } | Under mus‑händelser som orsakas av nedtryckning eller släpp av en musknapp, måste attributet button användas för att ange vilken pekarenhet‑knapp som ändrade tillstånd. |
| [Buttons](../../aspose.svg.dom.events/mouseevent/buttons/) { get; } | Under alla mus‑händelser måste attributet buttons användas för att ange vilken kombination av musknappar som för närvarande är nedtryckta, uttryckt som en bitmask. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Används för att ange om en händelse kan ha sin standardåtgärd förhindrad eller inte. Om standardåtgärden kan förhindras är värdet true, annars är värdet false. |
| [ClientX](../../aspose.svg.dom.events/mouseevent/clientx/) { get; } | Den horisontella koordinaten där händelsen inträffade i förhållande till den vyport som är associerad med händelsen. |
| [ClientY](../../aspose.svg.dom.events/mouseevent/clienty/) { get; } | Den vertikala koordinaten där händelsen inträffade i förhållande till den vyport som är associerad med händelsen. |
| [CtrlKey](../../aspose.svg.dom.events/mouseevent/ctrlkey/) { get; } | Se attributet ctrlKey. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Används för att ange den [`IEventTarget`](../ieventtarget/) vars [`IEventListener`](../ieventlistener/)s för närvarande bearbetas. Detta är särskilt användbart under fångst och bubbla. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Returnerar true om preventDefault() anropades medan cancelable-attributets värde är true, annars false. |
| [DeltaMode](../../aspose.svg.dom.events/wheelevent/deltamode/) { get; } | Attributet deltaMode innehåller en indikation på enheterna för mätning av delta‑värdena. Standardvärdet är DOM_DELTA_PIXEL (pixlar). |
| [DeltaX](../../aspose.svg.dom.events/wheelevent/deltax/) { get; } | I användaragenter där standardåtgärden för hjulhändelsen är att rulla, måste värdet vara mätningen längs x‑axeln (i pixlar, rader eller sidor) som ska rullas när händelsen inte avbryts. Annars är detta en implementation‑specifik mätning (i pixlar, rader eller sidor) av rörelsen hos en hjulenhet runt x‑axeln. |
| [DeltaY](../../aspose.svg.dom.events/wheelevent/deltay/) { get; } | I användaragenter där standardåtgärden för hjulhändelsen är att rulla, måste värdet vara mätningen längs y‑axeln (i pixlar, rader eller sidor) som ska rullas när händelsen inte avbryts. Annars är detta en implementation‑specifik mätning (i pixlar, rader eller sidor) av rörelsen hos en hjulenhet runt y‑axeln. |
| [DeltaZ](../../aspose.svg.dom.events/wheelevent/deltaz/) { get; } | I användaragenter där standardåtgärden för hjulhändelsen är att rulla, måste värdet vara mätningen längs z‑axeln (i pixlar, rader eller sidor) som ska rullas när händelsen inte avbryts. Annars är detta en implementation‑specifik mätning (i pixlar, rader eller sidor) av rörelsen hos en hjulenhet runt z‑axeln. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Anger viss detaljerad information om eventet, beroende på vilken typ av event det är. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Används för att ange vilken fas av händelseflödet som för närvarande utvärderas. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted-attributet måste returnera det värde det initierades med. När en händelse skapas måste attributet initieras till false. |
| [MetaKey](../../aspose.svg.dom.events/mouseevent/metakey/) { get; } | Se attributet metaKey. |
| [RelatedTarget](../../aspose.svg.dom.events/mouseevent/relatedtarget/) { get; } | Används för att identifiera ett sekundärt EventTarget relaterat till ett UI‑händelse, beroende på händelsetypen. |
| [ScreenX](../../aspose.svg.dom.events/mouseevent/screenx/) { get; } | Den horisontella koordinaten där händelsen inträffade i förhållande till ursprunget för skärmkoordinatsystemet. |
| [ScreenY](../../aspose.svg.dom.events/mouseevent/screeny/) { get; } | Den vertikala koordinaten där händelsen inträffade i förhållande till ursprunget för skärmkoordinatsystemet. |
| [ShiftKey](../../aspose.svg.dom.events/mouseevent/shiftkey/) { get; } | Se attributet shiftKey. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Används för att ange den [`IEventTarget`](../ieventtarget/) till vilken händelsen ursprungligen skickades. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Används för att ange tiden (i millisekunder relativt till epoken) då händelsen skapades. På grund av att vissa system kanske inte tillhandahåller denna information kan värdet för timeStamp vara otillgängligt för vissa händelser. När det inte är tillgängligt returneras värdet 0. Exempel på epoktider är systemets starttid eller 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Namnet på händelsen (skiftlägesokänsligt). Namnet måste vara ett XML‑namn. |
| [View](../../aspose.svg.dom.events/uievent/view/) { get; } | Attributet view identifierar det fönster från vilket eventet genererades. Det oinitierade värdet för detta attribut MÅSTE vara null. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Metoden [`InitEvent`](../event/initevent/) används för att initiera värdet av ett [`Event`](../event/) som skapats via gränssnittet [`IDocumentEvent`](../idocumentevent/). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Om ett event är avbrytbart, används metoden [`PreventDefault`](../event/preventdefault/) för att ange att eventet ska avbrytas, vilket betyder att någon standardåtgärd som normalt utförs av implementationen som ett resultat av eventet inte kommer att inträffa. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar att eventet når någon event listeners som registrerats efter den aktuella och när den dispatchas i ett träd förhindrar den också att eventet når andra objekt. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Metoden [`StopPropagation`](../event/stoppropagation/) används för att förhindra vidare spridning av ett event under eventflödet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DOM_DELTA_LINE](../../aspose.svg.dom.events/wheelevent/dom_delta_line/) | Måttenheterna för delta MÅSTE vara individuella textrader. Detta är fallet för många formulärkontroller. |
| const [DOM_DELTA_PAGE](../../aspose.svg.dom.events/wheelevent/dom_delta_page/) | Måttenheterna för delta MÅSTE vara sidor, antingen definierade som en enda skärm eller som en avgränsad sida. |
| const [DOM_DELTA_PIXEL](../../aspose.svg.dom.events/wheelevent/dom_delta_pixel/) | Måttenheterna för delta MÅSTE vara pixlar. Detta är det vanligaste fallet i de flesta operativsystem och implementationskonfigurationer. |

### Se även

* class [MouseEvent](../mouseevent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
