---
title: "Event-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Events.Event-klass. Event‑klassen används för att tillhandahålla kontextuell information om en händelse till den hanterare som bearbetar händelsen"
type: docs
weight: 2920
url: /sv/net/aspose.svg.dom.events/event/
---
## Event class

`Event` används för att tillhandahålla kontextuell information om en händelse till den hanterare som bearbetar händelsen.

```csharp
public class Event : DOMObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Event](event/#constructor)(*string*) | Initierar en ny instans av `Event`-klassen. |
| [Event](event/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Initierar en ny instans av `Event`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Används för att ange om en händelse är en bubblande händelse eller inte. Om händelsen kan bubbla är värdet true, annars är värdet false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Används för att ange om en händelse kan ha sin standardåtgärd förhindrad eller inte. Om standardåtgärden kan förhindras är värdet true, annars är värdet false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Används för att ange den [`IEventTarget`](../ieventtarget/) vars [`IEventListener`](../ieventlistener/)s för närvarande bearbetas. Detta är särskilt användbart under fångst och bubbla. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Returnerar true om preventDefault() anropades medan cancelable-attributets värde är true, annars false. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Används för att ange vilken fas av händelseflödet som för närvarande utvärderas. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted-attributet måste returnera det värde det initierades med. När en händelse skapas måste attributet initieras till false. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Används för att ange den [`IEventTarget`](../ieventtarget/) till vilken händelsen ursprungligen skickades. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Används för att ange tiden (i millisekunder relativt till epoken) då händelsen skapades. På grund av att vissa system kanske inte tillhandahåller denna information kan värdet för timeStamp vara otillgängligt för vissa händelser. När det inte är tillgängligt returneras värdet 0. Exempel på epoktider är systemets starttid eller 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Namnet på händelsen (skiftlägesokänsligt). Namnet måste vara ett XML‑namn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Metoden [`InitEvent`](./initevent/) används för att initiera värdet för ett `Event` som skapats via gränssnittet [`IDocumentEvent`](../idocumentevent/). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas används metoden [`PreventDefault`](./preventdefault/) för att ange att händelsen ska avbrytas, vilket innebär att någon standardåtgärd som normalt utförs av implementationen till följd av händelsen inte kommer att ske. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar att eventet når någon event listeners som registrerats efter den aktuella och när den dispatchas i ett träd förhindrar den också att eventet når andra objekt. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Metoden [`StopPropagation`](./stoppropagation/) används för att förhindra ytterligare spridning av en händelse under händelseflödet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [AtTargetPhase](../../aspose.svg.dom.events/event/attargetphase/) | Den aktuella händelsefasen är fångstfasen. |
| const [BubblingPhase](../../aspose.svg.dom.events/event/bubblingphase/) | Den aktuella händelsefasen är bubbelfasen. |
| const [CapturingPhase](../../aspose.svg.dom.events/event/capturingphase/) | Händelsen utvärderas för närvarande vid målet [`IEventTarget`](../ieventtarget/). |
| const [NonePhase](../../aspose.svg.dom.events/event/nonephase/) | Händelser som för närvarande inte har distribuerats befinner sig i denna fas. |

## Anmärkningar

Ett objekt som implementerar `Event` skickas vanligtvis som den första parametern till en händelsehanterare. Mer specifik kontextinformation skickas till händelsehanterare genom att härleda ytterligare gränssnitt från `Event` som innehåller information som direkt relaterar till typen av händelse de följer. Dessa härledda gränssnitt implementeras också av objektet som skickas till händelselyssnaren.

### Se även

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
