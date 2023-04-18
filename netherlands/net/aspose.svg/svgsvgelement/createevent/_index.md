---
title: SVGSVGElement.CreateEvent
second_title: Aspose.SVG voor .NET API-referentie
description: SVGSVGElement methode. Creëert eenEvent van een type dat wordt ondersteund door de implementatie.
type: docs
weight: 110
url: /nl/net/aspose.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Creëert een[`Event`](../../../aspose.svg.dom.events/event/) van een type dat wordt ondersteund door de implementatie.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | String | De parameter eventType specificeert het type van[`Event`](../../../aspose.svg.dom.events/event/) aan te maken interface.  Als de[`Event`](../../../aspose.svg.dom.events/event/)gespecificeerde interface wordt ondersteund door de implementatie deze methode retourneert een new [`Event`](../../../aspose.svg.dom.events/event/) van het aangevraagde interfacetype. Als de[`Event`](../../../aspose.svg.dom.events/event/)wordt verzonden via de[`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) methode de juiste [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/) methode moet na het maken worden aangeroepen om het[`Event`](../../../aspose.svg.dom.events/event/) s waarden. |

### Winstwaarde

De nieuw gemaakte[`Event`](../../../aspose.svg.dom.events/event/)

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Verhoogd als de implementatie het type[`Event`](../../../aspose.svg.dom.events/event/) interface aangevraagd |

### Zie ook

* class [Event](../../../aspose.svg.dom.events/event/)
* class [SVGSVGElement](../)
* naamruimte [Aspose.Svg](../../svgsvgelement/)
* montage [Aspose.SVG](../../../)


