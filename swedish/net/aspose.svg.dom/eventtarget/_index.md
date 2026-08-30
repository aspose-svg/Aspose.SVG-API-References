---
title: "EventTarget klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.EventTarget-klass. EventTarget‑gränssnittet implementeras av alla Nodes i en implementation som stöder DOM‑händelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika kastningsmetoder på en instans av Node‑gränssnittet. Gränssnittet möjliggör registrering och borttagning av händelselyssnare på ett EventTarget och sändning av händelser till den IEventTarget."
type: docs
weight: 2870
url: /sv/net/aspose.svg.dom/eventtarget/
---
## EventTarget class

`EventTarget`‑gränssnittet implementeras av alla Nodes i en implementation som stöder DOM‑händelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika kastningsmetoder på en instans av Node‑gränssnittet. Gränssnittet möjliggör registrering och borttagning av händelselyssnare på ett `EventTarget` och sändning av händelser till den [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/).

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EventTarget](eventtarget/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener_2)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Skickar ett Event till den angivna [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synkront) och anropar de påverkade EventListeners i rätt ordning. De vanliga reglerna för händelsebehandling (inklusive fångst‑ och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett `EventTarget` medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett `EventTarget` medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett `EventTarget` medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |

### Se även

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
