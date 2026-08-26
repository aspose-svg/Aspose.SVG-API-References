---
title: "MediaQueryList Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Window.MediaQueryList Klasse. Ein MediaQueryList-Objekt speichert Informationen zu einer Media-Query, die auf ein Dokument angewendet wird, und unterstützt sowohl sofortige als auch ereignisgesteuerte Übereinstimmungen mit dem Zustand des Dokuments. Siehe CSSOM View Module Specification https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /de/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

Ein MediaQueryList‑Objekt speichert Informationen zu einer auf ein Dokument angewendeten Medienabfrage und unterstützt sowohl sofortige als auch ereignisgesteuerte Übereinstimmungen mit dem Zustand des Dokuments. Siehe die CSSOM View Module specification: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | Dem Kontextobjekt zugehöriges Dokument. |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | Ein boolescher Wert, der true zurückgibt, wenn das Dokument derzeit mit der Media‑Query‑Liste übereinstimmt, oder false, wenn nicht. |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | Eine Zeichenkette, die eine serialisierte Media‑Query darstellt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Fügt einen Ereignislistener für Zustandsänderungen von MediaQueryList‑Übereinstimmungen hinzu. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Sendet ein Event an das angegebene [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListeners in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Capture‑ und optionalen Bubbling‑Phase) gelten ebenfalls für manuell mit [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/) gesendete Events. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Event‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../../aspose.svg.dom/eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach ihrer Entfernung niemals mehr aufgerufen werden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Event‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../../aspose.svg.dom/eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach ihrer Entfernung niemals mehr aufgerufen werden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Event‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../../aspose.svg.dom/eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach ihrer Entfernung niemals mehr aufgerufen werden. |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Entfernt den Ereignislistener für Zustandsänderungen von MediaQueryList‑Übereinstimmungen. |

## Ereignisse

| Name | Beschreibung |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | Ereignis, das bei der MediaQueryList ausgelöst wird, wenn sich der Übereinstimmungszustand ändert. |

### Siehe auch

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
