---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "EventTarget DispatchEvent‑methode. Verzendt een Event naar de opgegeven IEventTarget synchronisch en roept de getroffen EventListeners in de juiste volgorde aan. De normale regels voor event‑verwerking, inclusief de capture‑ en optionele bubbling‑fase, zijn ook van toepassing op handmatig met DispatchEvent verzonden events."
type: docs
weight: 30
url: /nl/net/aspose.svg.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Verzendt een Event naar de opgegeven [`IEventTarget`](../../../aspose.svg.dom.events/ieventtarget/), (synchronisch) en roept de getroffen EventListeners in de juiste volgorde aan. De normale regels voor event‑verwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig met [`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/) verzonden events.

```csharp
public bool DispatchEvent(Event @event)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| event | Evenement | Specificeert het gebeurtenistype, gedrag en contextuele informatie die bij het verwerken van het event worden gebruikt. |

### Retourwaarde

De retourwaarde van `DispatchEvent` geeft aan of een van de listeners die het event hebben afgehandeld, [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/) hebben aangeroepen. Als [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/) is aangeroepen, is de waarde false; anders is de waarde true.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../domexception/) |  |

## Opmerkingen

Events die op deze manier worden verzonden, hebben hetzelfde capture‑ en bubbling‑gedrag als events die rechtstreeks door de implementatie worden verzonden. Het doel van het event is de [`EventTarget`](../) waarop `DispatchEvent` wordt aangeroepen.

### Zie ook

* class [Event](../../../aspose.svg.dom.events/event/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
