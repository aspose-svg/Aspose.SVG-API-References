---
title: "MediaQueryList-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Window.MediaQueryList-klass. Ett MediaQueryList-objekt lagrar information om en mediaselektion som tillämpas på ett dokument med stöd för både omedelbar och händelsedriven matchning mot dokumentets tillstånd. Se CSSOM View Module-specifikationen https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /sv/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

Ett MediaQueryList-objekt lagrar information om en mediaselektion som tillämpas på ett dokument, med stöd för både omedelande och händelsedriven matchning mot dokumentets tillstånd. Se CSSOM View Module-specifikationen: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | Context-objektets associerade dokument. |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | Ett booleskt värde som returnerar true om dokumentet för närvarande matchar mediaselektionen, annars false. |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | En sträng som representerar en serialiserad mediaselektion. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Lägg till en MediaQueryList‑lyssnare för ändring av matchningsstatus. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Skickar ett Event till den angivna [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synkront) och anropar de påverkade EventListeners i rätt ordning. De vanliga reglerna för händelsebehandling (inklusive fångst‑ och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../../aspose.svg.dom/eventtarget/) medan det bearbetar en händelse, kommer den inte att triggas av de pågående åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../../aspose.svg.dom/eventtarget/) medan det bearbetar en händelse, kommer den inte att triggas av de pågående åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../../aspose.svg.dom/eventtarget/) medan det bearbetar en händelse, kommer den inte att triggas av de pågående åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Ta bort MediaQueryList‑lyssnare för ändring av matchningsstatus. |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | Händelse som avfyras på MediaQueryList när matchningsstatusen ändras. |

### Se även

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
