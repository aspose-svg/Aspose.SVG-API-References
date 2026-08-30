---
title: "KeyboardEvent-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Events.KeyboardEvent-klass. KeyboardEvent‑gränssnittet tillhandahåller specifik kontextuell information som är kopplad till tangentbordsenheter. Varje tangentbords‑event refererar till en tangent med ett värde. Tangentbords‑event riktas vanligtvis mot det element som har fokus."
type: docs
weight: 2980
url: /sv/net/aspose.svg.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent-gränssnittet tillhandahåller specifik kontextuell information som är associerad med tangentbordsenheter. Varje tangentbordshändelse refererar till en tangent med ett värde. Tangentbordshändelser riktas vanligtvis mot det element som har fokus.

```csharp
public class KeyboardEvent : UIEvent
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(*string*) | Initierar en ny instans av klassen `KeyboardEvent`. |
| [KeyboardEvent](keyboardevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Initierar en ny instans av klassen `KeyboardEvent`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/keyboardevent/altkey/) { get; } | true om Alt‑tangenten (alternativ) (eller "Option") var aktiv. Det oinitierade värdet för detta attribut MÅSTE vara false. |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Används för att ange om en händelse är en bubblande händelse eller inte. Om händelsen kan bubbla är värdet true, annars är värdet false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Används för att ange om en händelse kan ha sin standardåtgärd förhindrad eller inte. Om standardåtgärden kan förhindras är värdet true, annars är värdet false. |
| [Code](../../aspose.svg.dom.events/keyboardevent/code/) { get; } | Koden innehåller en sträng som identifierar den fysiska tangent som trycks ned. Värdet påverkas inte av det aktuella tangentbordslayouten eller modifierartillståndet, så en viss tangent kommer alltid att returnera samma värde. |
| [CtrlKey](../../aspose.svg.dom.events/keyboardevent/ctrlkey/) { get; } | true om Control‑tangenten (control) var aktiv. Det oinitierade värdet för detta attribut MÅSTE vara false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Används för att ange den [`IEventTarget`](../ieventtarget/) vars [`IEventListener`](../ieventlistener/)s för närvarande bearbetas. Detta är särskilt användbart under fångst och bubbla. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Returnerar true om preventDefault() anropades medan cancelable-attributets värde är true, annars false. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Anger viss detaljerad information om eventet, beroende på vilken typ av event det är. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Används för att ange vilken fas av händelseflödet som för närvarande utvärderas. |
| [IsComposing](../../aspose.svg.dom.events/keyboardevent/iscomposing/) { get; } | true om tangentbords‑eventet inträffar som en del av en kompositionssession, d.v.s. efter ett compositionstart‑event och före motsvarande compositionend‑event. Det oinitierade värdet för detta attribut MÅSTE vara false. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted-attributet måste returnera det värde det initierades med. När en händelse skapas måste attributet initieras till false. |
| [Key](../../aspose.svg.dom.events/keyboardevent/key/) { get; } | Nyckeln innehåller nyckelvärdet för den tryckta tangenten. Om värdet har en tryckt representation MÅSTE det vara en icke‑tom Unicode‑teckensekvens som följer algoritmen för att bestämma nyckelvärdet som definieras i denna specifikation. Om värdet är en kontrolltangent utan tryckt representation MÅSTE det vara ett av nyckelvärdena som definieras i nyckelvärdesuppsättningen, enligt algoritmen för att bestämma nyckelvärdet. Implementationer som inte kan identifiera en tangent MÅSTE använda nyckelvärdet Unidentified. |
| [Location](../../aspose.svg.dom.events/keyboardevent/location/) { get; } | Attributet location innehåller en indikation på den logiska placeringen av tangenten på enheten. |
| [MetaKey](../../aspose.svg.dom.events/keyboardevent/metakey/) { get; } | true om meta‑tangenten (Meta) var aktiv. |
| [Repeat](../../aspose.svg.dom.events/keyboardevent/repeat/) { get; } | true om tangenten har hållits ned under en längre tid. Att hålla ner en tangent MÅSTE leda till att händelserna keydown, beforeinput, input upprepas i den ordningen, med en frekvens som bestäms av systemkonfigurationen. För mobila enheter som har långtangent‑beteende måste det första tangent‑eventet med repeat‑attributvärdet true fungera som en indikation på ett långtangent‑tryck. Den tid som tangenten MÅSTE hållas ned för att börja upprepa är konfigurationsberoende. |
| [ShiftKey](../../aspose.svg.dom.events/keyboardevent/shiftkey/) { get; } | true om shift‑tangenten (Shift) var aktiv. |
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
| const [DOM_KEY_LOCATION_LEFT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_left/) | Den aktiverade tangenten härstammar från den vänstra tangentplatsen (när det finns mer än en möjlig plats för den här tangenten). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_numpad/) | Tangentaktiveringen härstammar från det numeriska tangentbordet eller med en virtuell tangent som motsvarar det numeriska tangentbordet (när det finns mer än en möjlig plats för denna tangent). Observera att NumLock‑tangenten alltid ska kodas med platsen DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_right/) | Tangentaktiveringen härstammar från den högra tangentplatsen (när det finns mer än en möjlig plats för den här tangenten). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_standard/) | Tangentaktiveringen FÅR INTE särskiljas som den vänstra eller högra versionen av tangenten, och (förutom NumLock‑tangenten) härstammade inte från det numeriska tangentbordet (eller från en virtuell tangent som motsvarar det numeriska tangentbordet). |

### Se även

* class [UIEvent](../uievent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
