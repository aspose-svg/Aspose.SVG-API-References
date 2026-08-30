---
title: "TimeEvent-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Events.TimeEvent-klass. TimeEvent-gränssnittet tillhandahåller specifik kontextuell information kopplad till tids‑händelser. De olika typerna av händelser som kan förekomma är beginEvent, endEvent och repeatEvent."
type: docs
weight: 3720
url: /sv/net/aspose.svg.events/timeevent/
---
## TimeEvent class

TimeEvent‑gränssnittet tillhandahåller specifik kontextuell information som är associerad med tidshändelser. De olika typerna av händelser som kan förekomma är: beginEvent, endEvent och repeatEvent.

```csharp
public class TimeEvent : Event
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Används för att ange om en händelse är en bubblande händelse eller inte. Om händelsen kan bubbla är värdet true, annars är värdet false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Används för att ange om en händelse kan ha sin standardåtgärd förhindrad eller inte. Om standardåtgärden kan förhindras är värdet true, annars är värdet false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Används för att ange [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) vars [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)s för närvarande bearbetas. Detta är särskilt användbart under fångst och bubbla. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Returnerar true om preventDefault() anropades medan cancelable-attributets värde är true, annars false. |
| [Detail](../../aspose.svg.events/timeevent/detail/) { get; } | Specificerar viss detaljerad information om händelsen, beroende på händelsetypen. För denna händelsetyp anger den repetitionsnumret för animationen. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Används för att ange vilken fas av händelseflödet som för närvarande utvärderas. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted-attributet måste returnera det värde det initierades med. När en händelse skapas måste attributet initieras till false. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Används för att ange [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) till vilken händelsen ursprungligen skickades. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Används för att ange tiden (i millisekunder relativt till epoken) då händelsen skapades. På grund av att vissa system kanske inte tillhandahåller denna information kan värdet för timeStamp vara otillgängligt för vissa händelser. När det inte är tillgängligt returneras värdet 0. Exempel på epoktider är systemets starttid eller 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Namnet på händelsen (skiftlägesokänsligt). Namnet måste vara ett XML‑namn. |
| [View](../../aspose.svg.events/timeevent/view/) { get; } | View-attributet identifierar AbstractView [DOM2VIEWS] från vilken händelsen genererades. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Metoden [`InitEvent`](../../aspose.svg.dom.events/event/initevent/) används för att initiera värdet av ett [`Event`](../../aspose.svg.dom.events/event/) skapat via [`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/)-gränssnittet. |
| [InitTimeEvent](../../aspose.svg.events/timeevent/inittimeevent/)(*string, [IAbstractView](../../aspose.svg.dom.views/iabstractview/), long*) | Metoden initTimeEvent används för att initiera värdet av ett TimeEvent skapat via DocumentEvent‑gränssnittet. Denna metod får endast anropas innan TimeEvent har skickats via dispatchEvent‑metoden, men den kan anropas flera gånger under den fasen om så behövs. Om den anropas flera gånger har det sista anropet företräde. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas används metoden [`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/) för att indikera att händelsen ska avbrytas, vilket betyder att någon standardåtgärd som normalt utförs av implementationen som ett resultat av händelsen inte kommer att ske. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar att eventet når någon event listeners som registrerats efter den aktuella och när den dispatchas i ett träd förhindrar den också att eventet når andra objekt. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Metoden [`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/) används för att förhindra vidare spridning av en händelse under händelseflödet. |

### Se även

* class [Event](../../aspose.svg.dom.events/event/)
* namespace [Aspose.Svg.Events](../../aspose.svg.events/)
* assembly [Aspose.SVG](../../)
