---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "IDocumentEvent CreateEvent-methode. Maakt een Event van een type dat door de implementatie wordt ondersteund."
type: docs
weight: 10
url: /nl/net/aspose.svg.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Maakt een [`Event`](../../event/) van een type dat door de implementatie wordt ondersteund.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | String | De parameter eventType geeft het type van de [`Event`](../../event/) interface op dat moet worden aangemaakt. Als de opgegeven [`Event`](../../event/) interface door de implementatie wordt ondersteund, zal deze methode een nieuwe [`Event`](../../event/) van het gevraagde interface‑type retourneren. Als de [`Event`](../../event/) moet worden verzonden via de [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/)‑methode, moet de juiste [`InitEvent`](../../event/initevent/)‑methode na de creatie worden aangeroepen om de waarden van de [`Event`](../../event/) te initialiseren. |

### Retourwaarde

De nieuw aangemaakte [`Event`](../../event/)

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Opgegooid als de implementatie het gevraagde type van de [`Event`](../../event/) interface niet ondersteunt |

### Zie ook

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
