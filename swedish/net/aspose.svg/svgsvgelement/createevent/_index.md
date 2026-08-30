---
title: "SVGSVGElement.CreateEvent"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGSVGElement CreateEvent‑metod. Skapar ett Event av en typ som stöds av implementationen."
type: docs
weight: 110
url: /sv/net/aspose.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Skapar ett [`Event`](../../../aspose.svg.dom.events/event/) av en typ som stöds av implementationen.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | String | eventType‑parametern specificerar typen av [`Event`](../../../aspose.svg.dom.events/event/)‑gränssnitt som ska skapas. Om det specificerade [`Event`](../../../aspose.svg.dom.events/event/)‑gränssnittet stöds av implementationen kommer denna metod att returnera ett nytt [`Event`](../../../aspose.svg.dom.events/event/) av den begärda gränssnittstypen. Om [`Event`](../../../aspose.svg.dom.events/event/) ska skickas via [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/)‑metoden måste den lämpliga [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/)‑metoden anropas efter skapandet för att initiera [`Event`](../../../aspose.svg.dom.events/event/)-värdena. |

### Returvärde

Det nyss skapade [`Event`](../../../aspose.svg.dom.events/event/)

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Uppstår om implementationen inte stöder den begärda typen av [`Event`](../../../aspose.svg.dom.events/event/)-gränssnitt |

### Se även

* class [Event](../../../aspose.svg.dom.events/event/)
* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
