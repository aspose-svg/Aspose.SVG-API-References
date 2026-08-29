---
title: "IEventTarget.DispatchEvent"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "IEventTarget DispatchEvent-methode. Deze methode maakt het verzenden van events in het eventmodel van de implementatie mogelijk."
type: docs
weight: 20
url: /nl/net/aspose.svg.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Deze methode maakt het verzenden van gebeurtenissen in het eventmodel van de implementatie mogelijk.

```csharp
public bool DispatchEvent(Event @event)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| event | Evenement | Specificeert het gebeurtenistype, gedrag en contextuele informatie die bij het verwerken van het event worden gebruikt. |

### Retourwaarde

De retourwaarde van [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) geeft aan of een van de listeners die het event hebben afgehandeld [`PreventDefault`](../../event/preventdefault/) hebben aangeroepen. Als [`PreventDefault`](../../event/preventdefault/) is aangeroepen, is de waarde false, anders is de waarde true.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) |  |

## Opmerkingen

Events die op deze manier worden verzonden, hebben hetzelfde capture- en bubbling-gedrag als events die rechtstreeks door de implementatie worden verzonden. Het doel van het event is de [`EventTarget`](../../../aspose.svg.dom/eventtarget/) waarop [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) wordt aangeroepen.

### Zie ook

* class [Event](../../event/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
