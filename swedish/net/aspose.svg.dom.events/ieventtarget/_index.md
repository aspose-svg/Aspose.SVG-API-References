---
title: "IEventTarget‑gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Events.IEventTarget‑gränssnitt. EventTarget‑gränssnittet implementeras av alla noder i en implementation som stödjer DOM‑händelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika cast‑metoder på en instans av Node‑gränssnittet. Gränssnittet möjliggör registrering och borttagning av Event Listeners på ett EventTarget och sändning av händelser till det IEventTarget."
type: docs
weight: 2960
url: /sv/net/aspose.svg.dom.events/ieventtarget/
---
## IEventTarget interface

Det [`EventTarget`](../../aspose.svg.dom/eventtarget/)‑gränssnittet implementeras av alla noder i en implementation som stödjer DOM‑händelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika cast‑metoder på en instans av Node‑gränssnittet. Gränssnittet möjliggör registrering och borttagning av Event Listeners på ett [`EventTarget`](../../aspose.svg.dom/eventtarget/) och sändning av händelser till den `IEventTarget`.

```csharp
public interface IEventTarget
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener)(*string, [IEventListener](../ieventlistener/)*) | Denna metod möjliggör registrering av händelselyssnare på händelsemålet. |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | Denna metod möjliggör registrering av händelselyssnare på händelsemålet. |
| [DispatchEvent](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)(*[Event](../event/)*) | Denna metod möjliggör sändning av händelser till implementationens händelsemodell. |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(*string, [IEventListener](../ieventlistener/)*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../ieventlistener/) tas bort från ett [`EventTarget`](../../aspose.svg.dom/eventtarget/) medan den bearbetar en händelse, kommer den inte att utlösas av de pågående åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../ieventlistener/) tas bort från ett [`EventTarget`](../../aspose.svg.dom/eventtarget/) medan den bearbetar en händelse, kommer den inte att utlösas av de pågående åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |

### Se även

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
