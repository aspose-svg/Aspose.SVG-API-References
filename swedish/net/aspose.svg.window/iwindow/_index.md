---
title: "IWindow-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Window.IWindow-gränssnitt. Fönsterobjektet representerar ett fönster som innehåller ett DOM-dokument"
type: docs
weight: 5920
url: /sv/net/aspose.svg.window/iwindow/
---
## IWindow interface

Fönsterobjektet representerar ett fönster som innehåller ett DOM-dokument.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document/) { get; } | document-attributet måste returnera Window-objektets senaste Document-objekt. |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement/) { get; } | frameElement-objektet för ett Document. |
| [LocalStorage](../../aspose.svg.window/iwindow/localstorage/) { get; } | Returnerar ett Storage-objekt som låter dig spara nyckel/värde-par i användaragenten. |
| [Location](../../aspose.svg.window/iwindow/location/) { get; } | location-attributet för Window-gränssnittet måste returnera Location-objektet för det Window-objektets Document. |
| [Name](../../aspose.svg.window/iwindow/name/) { get; set; } | name-attributet för Window-objektet måste, vid läsning, returnera det aktuella namnet på surfkontexten, och, vid skrivning, sätta namnet på surfkontexten till det nya värdet. |
| [Opener](../../aspose.svg.window/iwindow/opener/) { get; } | opener IDL-attributet på Window-objektet, vid läsning, måste returnera WindowProxy-objektet för den surfkontext som den aktuella surfkontexten skapades från (dess opener-surfkontext), om ett sådant finns, om det fortfarande är tillgängligt, och om den aktuella surfkontexten inte har avstått sitt opener; annars måste det returnera null. Vid skrivning, om det nya värdet är null ska den aktuella surfkontexten avstå sitt opener; om det nya värdet är något annat ska användaragenten anropa den interna metoden [[DefineOwnProperty]] för Window-objektet, skicka egenskapsnamnet "opener" som nyckel, och Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } som egenskapsbeskrivning, där value är det nya värdet. |
| [Parent](../../aspose.svg.window/iwindow/parent/) { get; } | parent IDL-attributet på Window-objektet för ett Document i en surfkontext b måste returnera WindowProxy-objektet för den överordnade surfkontexten, om ett sådant finns (dvs. om b är en barn-surfkontext), eller WindowProxy-objektet för surfkontexten b själv, annars (dvs. om det är en toppnivå-surfkontext eller en fristående nästlad surfkontext). |
| [Self](../../aspose.svg.window/iwindow/self/) { get; } | Returnerar Window-objektets surfkontexts WindowProxy-objekt. |
| [Top](../../aspose.svg.window/iwindow/top/) { get; } | top IDL-attributet på Window-objektet för ett Document i en surfkontext b måste returnera WindowProxy-objektet för dess toppnivå-surfkontext (vilket skulle vara dess eget WindowProxy-objekt om det var en toppnivå-surfkontext), om det har ett, eller dess eget WindowProxy-objekt annars (t.ex. om det var en fristående nästlad surfkontext). |
| [Window](../../aspose.svg.window/iwindow/window/) { get; } | Returnerar Window-objektets surfkontexts WindowProxy-objekt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert/)(*string*) | Visar en modal varning med det angivna meddelandet och väntar på att användaren avfärdar den |
| [Atob](../../aspose.svg.window/iwindow/atob/)(*string*) | Tar emot indata i form av en Unicode-sträng som innehåller base64-kodad binär data, avkodar den och returnerar en sträng bestående av tecken i intervallet U+0000 till U+00FF, där varje tecken representerar en binär byte med värden 0x00 till 0xFF respektive, motsvarande den binära datan. |
| [Btoa](../../aspose.svg.window/iwindow/btoa/)(*string*) | Tar emot indata i form av en Unicode-sträng som endast innehåller tecken i intervallet U+0000 till U+00FF, där varje tecken representerar en binär byte med värden 0x00 till 0xFF respektive, och konverterar den till dess base64-representation, som den returnerar. |
| [Confirm](../../aspose.svg.window/iwindow/confirm/)(*string*) | Visar en modal OK/Avbryt‑prompt med det angivna meddelandet, väntar på att användaren avfärdar den och returnerar true om användaren klickar på OK och false om användaren klickar på Avbryt. |
| [MatchMedia](../../aspose.svg.window/iwindow/matchmedia/)(*string*) | Returnerar ett nytt MediaQueryList‑objekt som sedan kan användas för att avgöra om dokumentet matchar media‑frågesträngen, samt för att övervaka dokumentet för att upptäcka när det matchar (eller slutar matcha) den media‑frågan. Se CSSOM View Module‑specifikationen: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [Prompt](../../aspose.svg.window/iwindow/prompt/)(*string, string*) | Visar en modal textruta‑prompt med det angivna meddelandet, väntar på att användaren avfärdar den och returnerar det värde som användaren skrev in. Om användaren avbryter prompten returneras null istället. Om det andra argumentet finns, används det angivna värdet som standard. |

### Se även

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
