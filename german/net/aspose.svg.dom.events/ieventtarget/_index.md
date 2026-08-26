---
title: "IEventTarget Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Events.IEventTarget‑Schnittstelle. Die EventTarget‑Schnittstelle wird von allen Nodes in einer Implementierung, die das DOM‑Ereignismodell unterstützt, implementiert. Daher kann diese Schnittstelle durch bindungsspezifische Cast‑Methoden auf einer Instanz der Node‑Schnittstelle erhalten werden. Die Schnittstelle ermöglicht die Registrierung und das Entfernen von Event‑Listenern auf einem EventTarget sowie das Senden von Ereignissen an dieses IEventTarget."
type: docs
weight: 2960
url: /de/net/aspose.svg.dom.events/ieventtarget/
---
## IEventTarget interface

Die [`EventTarget`](../../aspose.svg.dom/eventtarget/)‑Schnittstelle wird von allen Nodes in einer Implementierung, die das DOM‑Ereignismodell unterstützt, implementiert. Daher kann diese Schnittstelle durch bindungsspezifische Cast‑Methoden auf einer Instanz der Node‑Schnittstelle erhalten werden. Die Schnittstelle ermöglicht die Registrierung und das Entfernen von Event‑Listenern auf einem [`EventTarget`](../../aspose.svg.dom/eventtarget/) und das Senden von Ereignissen an dieses `IEventTarget`.

```csharp
public interface IEventTarget
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener)(*string, [IEventListener](../ieventlistener/)*) | Diese Methode ermöglicht die Registrierung von Event‑Listenern auf dem Ereignisziel. |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | Diese Methode ermöglicht die Registrierung von Event‑Listenern auf dem Ereignisziel. |
| [DispatchEvent](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)(*[Event](../event/)*) | Diese Methode ermöglicht das Senden von Ereignissen in das Ereignismodell der Implementierung. |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(*string, [IEventListener](../ieventlistener/)*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Ereignisziel. Wenn ein [`IEventListener`](../ieventlistener/) von einem [`EventTarget`](../../aspose.svg.dom/eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Ereignisziel. Wenn ein [`IEventListener`](../ieventlistener/) von einem [`EventTarget`](../../aspose.svg.dom/eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach dem Entfernen niemals mehr aufgerufen werden. |

### Siehe auch

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
