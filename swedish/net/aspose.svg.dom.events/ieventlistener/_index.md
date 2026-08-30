---
title: "IEventListener-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Events.IEventListener-gränssnitt. IEventListener-gränssnittet är den primära metoden för att hantera händelser. Användare implementerar IEventListener-gränssnittet och registrerar sin lyssnare på ett EventTarget med hjälp av AddEventListener‑metoden. Användarna bör också ta bort sin IEventListener från dess EventTarget efter att de har slutfört användningen av lyssnaren."
type: docs
weight: 2950
url: /sv/net/aspose.svg.dom.events/ieventlistener/
---
## IEventListener interface

`IEventListener`-gränssnittet är den primära metoden för att hantera händelser. Användare implementerar `IEventListener`-gränssnittet och registrerar sin lyssnare på ett [`EventTarget`](../../aspose.svg.dom/eventtarget/) med hjälp av [`AddEventListener`](../../aspose.svg.dom/eventtarget/addeventlistener/)‑metoden. Användarna bör också ta bort sin `IEventListener` från dess [`EventTarget`](../../aspose.svg.dom/eventtarget/) efter att de har avslutat användningen av lyssnaren.

```csharp
public interface IEventListener
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [HandleEvent](../../aspose.svg.dom.events/ieventlistener/handleevent/)(*[Event](../event/)*) | Denna metod anropas närhelst en händelse av den typ som `IEventListener`-gränssnittet registrerades för inträffar. |

## Anmärkningar

När en Node kopieras med metoden cloneNode är de Event Listeners som är kopplade till käll‑Node:n inte kopplade till den kopierade Node:n. Om användaren vill att samma Event Listeners ska läggas till i den nyss skapade kopian måste användaren lägga till dem manuellt.

### Se även

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
