---
title: "InputEvent-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Events.InputEvent-klass. Inmatningshändelser skickas som aviseringar när DOM uppdateras"
type: docs
weight: 2970
url: /sv/net/aspose.svg.dom.events/inputevent/
---
## InputEvent class

Inmatningshändelser skickas som aviseringar närhelst DOM uppdateras.

```csharp
public class InputEvent : UIEvent
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [InputEvent](inputevent/#constructor)(*string*) | Initierar en ny instans av `InputEvent`-klassen. |
| [InputEvent](inputevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Initierar en ny instans av `InputEvent`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Används för att ange om en händelse är en bubblande händelse eller inte. Om händelsen kan bubbla är värdet true, annars är värdet false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Används för att ange om en händelse kan ha sin standardåtgärd förhindrad eller inte. Om standardåtgärden kan förhindras är värdet true, annars är värdet false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Används för att ange den [`IEventTarget`](../ieventtarget/) vars [`IEventListener`](../ieventlistener/)s för närvarande bearbetas. Detta är särskilt användbart under fångst och bubbla. |
| [Data](../../aspose.svg.dom.events/inputevent/data/) { get; } | Data innehåller värdet för de tecken som genereras av en inmatningsmetod. Detta KAN vara ett enskilt Unicode-tecken eller en icke‑tom sekvens av Unicode-tecken [Unicode]. Tecken SKALL normaliseras enligt Unicode‑normaliseringsformen NFC, definierad i [UAX15]. Detta attribut KAN innehålla en tom sträng. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Returnerar true om preventDefault() anropades medan cancelable-attributets värde är true, annars false. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Anger viss detaljerad information om eventet, beroende på vilken typ av event det är. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Används för att ange vilken fas av händelseflödet som för närvarande utvärderas. |
| [IsComposing](../../aspose.svg.dom.events/inputevent/iscomposing/) { get; } | Sant om inmatningshändelsen inträffar som en del av en kompositionssession, d.v.s. efter en compositionstart‑händelse och före motsvarande compositionend‑händelse. Det oinitialiserade värdet för detta attribut MÅSTE vara falskt. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted-attributet måste returnera det värde det initierades med. När en händelse skapas måste attributet initieras till false. |
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

### Se även

* class [UIEvent](../uievent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
