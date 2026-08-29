---
title: "IEventTarget-interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Events.IEventTarget interface. De EventTarget-interface wordt geïmplementeerd door alle Nodes in een implementatie die het DOM Event Model ondersteunt. Daarom kan deze interface worden verkregen door binding-specifieke castmethoden te gebruiken op een instantie van de Node-interface. De interface maakt registratie en verwijdering van Event Listeners op een EventTarget mogelijk en de dispatch van gebeurtenissen naar die IEventTarget."
type: docs
weight: 2960
url: /nl/net/aspose.svg.dom.events/ieventtarget/
---
## IEventTarget interface

De [`EventTarget`](../../aspose.svg.dom/eventtarget/) interface wordt geïmplementeerd door alle Nodes in een implementatie die het DOM Event Model ondersteunt. Daarom kan deze interface worden verkregen door binding‑specifieke cast‑methoden te gebruiken op een instantie van de Node‑interface. De interface maakt registratie en verwijdering van Event Listeners op een [`EventTarget`](../../aspose.svg.dom/eventtarget/) mogelijk en het verzenden van gebeurtenissen naar die `IEventTarget`.

```csharp
public interface IEventTarget
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener)(*string, [IEventListener](../ieventlistener/)*) | Deze methode maakt de registratie van event listeners op het event‑doel mogelijk. |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | Deze methode maakt de registratie van event listeners op het event‑doel mogelijk. |
| [DispatchEvent](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)(*[Event](../event/)*) | Deze methode maakt het verzenden van gebeurtenissen in het eventmodel van de implementatie mogelijk. |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(*string, [IEventListener](../ieventlistener/)*) | Deze methode maakt het verwijderen van event listeners van het event‑doel mogelijk. Als een [`IEventListener`](../ieventlistener/) wordt verwijderd van een [`EventTarget`](../../aspose.svg.dom/eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | Deze methode maakt het verwijderen van event listeners van het event‑doel mogelijk. Als een [`IEventListener`](../ieventlistener/) wordt verwijderd van een [`EventTarget`](../../aspose.svg.dom/eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |

### Zie ook

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
