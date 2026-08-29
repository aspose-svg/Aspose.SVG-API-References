---
title: "SVGSVGElement.CreateEvent"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGSVGElement CreateEvent-methode. Maakt een Event van een type dat door de implementatie wordt ondersteund."
type: docs
weight: 110
url: /nl/net/aspose.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Maakt een [`Event`](../../../aspose.svg.dom.events/event/) van een type dat door de implementatie wordt ondersteund.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | String | De parameter eventType geeft het type van de [`Event`](../../../aspose.svg.dom.events/event/) interface op die moet worden aangemaakt. Als de opgegeven [`Event`](../../../aspose.svg.dom.events/event/) interface wordt ondersteund door de implementatie, zal deze methode een nieuw [`Event`](../../../aspose.svg.dom.events/event/) van het gevraagde interfacetype retourneren. Als het [`Event`](../../../aspose.svg.dom.events/event/) moet worden verzonden via de [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) methode, moet de juiste [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/) methode na de creatie worden aangeroepen om de waarden van het [`Event`](../../../aspose.svg.dom.events/event/) te initialiseren. |

### Retourwaarde

De nieuw aangemaakte [`Event`](../../../aspose.svg.dom.events/event/)

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de implementatie het type van de gevraagde [`Event`](../../../aspose.svg.dom.events/event/) interface niet ondersteunt |

### Zie ook

* class [Event](../../../aspose.svg.dom.events/event/)
* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
