---
title: "EventTarget Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.EventTarget Klasse. Das EventTarget‑Interface wird von allen Nodes in einer Implementierung, die das DOM‑Ereignismodell unterstützt, implementiert. Daher kann dieses Interface mittels bindungsspezifischer Cast‑Methoden auf einer Instanz des Node‑Interfaces erhalten werden. Das Interface ermöglicht die Registrierung und das Entfernen von Event‑Listenern auf einem EventTarget sowie das Senden von Ereignissen an dieses IEventTarget."
type: docs
weight: 2870
url: /de/net/aspose.svg.dom/eventtarget/
---
## EventTarget class

Das `EventTarget`‑Interface wird von allen Nodes in einer Implementierung, die das DOM‑Ereignismodell unterstützt, implementiert. Daher kann dieses Interface mittels bindungsspezifischer Cast‑Methoden auf einer Instanz des Node‑Interfaces erhalten werden. Das Interface ermöglicht die Registrierung und das Entfernen von Event‑Listenern auf einem `EventTarget` und das Senden von Ereignissen an dieses [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/).

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [EventTarget](eventtarget/)() | Der Standard‑Konstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener_2)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Sendet ein Event an das angegebene [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListeners in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Capture‑ und optionalen Bubbling‑Phase) gelten ebenfalls für manuell mit [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/) gesendete Events. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Event‑Target. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem `EventTarget` entfernt wird, während dieser ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach ihrer Entfernung niemals mehr aufgerufen werden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Event‑Target. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem `EventTarget` entfernt wird, während dieser ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach ihrer Entfernung niemals mehr aufgerufen werden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Event‑Target. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem `EventTarget` entfernt wird, während dieser ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach ihrer Entfernung niemals mehr aufgerufen werden. |

### Siehe auch

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
