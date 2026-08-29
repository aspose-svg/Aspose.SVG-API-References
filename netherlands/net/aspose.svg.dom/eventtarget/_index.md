---
title: "EventTarget Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.EventTarget class. De EventTarget‑interface wordt geïmplementeerd door alle Nodes in een implementatie die het DOM‑evenementmodel ondersteunt. Daarom kan deze interface worden verkregen door bindings‑specifieke cast‑methoden te gebruiken op een instantie van de Node‑interface. De interface maakt registratie en verwijdering van Event Listeners op een EventTarget mogelijk en verzendt gebeurtenissen naar die IEventTarget"
type: docs
weight: 2870
url: /nl/net/aspose.svg.dom/eventtarget/
---
## EventTarget class

De `EventTarget`‑interface wordt geïmplementeerd door alle Nodes in een implementatie die het DOM‑evenementmodel ondersteunt. Daarom kan deze interface worden verkregen door bindings‑specifieke cast‑methoden te gebruiken op een instantie van de Node‑interface. De interface maakt registratie en verwijdering van Event Listeners op een `EventTarget` mogelijk en verzendt gebeurtenissen naar die [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/).

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [EventTarget](eventtarget/)() | De standaardconstructor. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener_2)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Verzendt een Event naar het opgegeven [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synchroon) en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor eventverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Deze methode maakt het verwijderen van event listeners van het event‑target mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een `EventTarget` terwijl deze een gebeurtenis verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Deze methode maakt het verwijderen van event listeners van het event‑target mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een `EventTarget` terwijl deze een gebeurtenis verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Deze methode maakt het verwijderen van event listeners van het event‑target mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een `EventTarget` terwijl deze een gebeurtenis verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |

### Zie ook

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
