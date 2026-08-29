---
title: "Document.CreateEvent"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Document CreateEvent-methode. Maakt een Event van een type dat door de implementatie wordt ondersteund"
type: docs
weight: 880
url: /nl/net/aspose.svg.dom/document/createevent/
---
## Document.CreateEvent method

Maakt een [`Event`](../../../aspose.svg.dom.events/event/) van een type dat door de implementatie wordt ondersteund.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | String | De parameter eventType specificeert het type van de [`Event`](../../../aspose.svg.dom.events/event/) interface die moet worden aangemaakt. Als de opgegeven [`Event`](../../../aspose.svg.dom.events/event/) interface wordt ondersteund door de implementatie, zal deze methode een nieuwe [`Event`](../../../aspose.svg.dom.events/event/) van het gevraagde interface‑type retourneren. Als de [`Event`](../../../aspose.svg.dom.events/event/) moet worden verzonden via de [`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/)‑methode, moet na het aanmaken de juiste [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/)‑methode worden aangeroepen om de waarden van de [`Event`](../../../aspose.svg.dom.events/event/) te initialiseren. |

### Retourwaarde

De nieuw aangemaakte [`Event`](../../../aspose.svg.dom.events/event/)

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de implementatie het type van de gevraagde [`Event`](../../../aspose.svg.dom.events/event/) interface niet ondersteunt |

### Zie ook

* class [Event](../../../aspose.svg.dom.events/event/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
