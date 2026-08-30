---
title: "Document.CreateEvent"
second_title: "Aspose.SVG för .NET API-referens"
description: "Document CreateEvent-metod. Skapar ett Event av en typ som stöds av implementationen"
type: docs
weight: 880
url: /sv/net/aspose.svg.dom/document/createevent/
---
## Document.CreateEvent method

Skapar ett [`Event`](../../../aspose.svg.dom.events/event/) av en typ som stöds av implementationen.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | String | Parametern eventType specificerar vilken typ av [`Event`](../../../aspose.svg.dom.events/event/)-gränssnitt som ska skapas.  Om det angivna [`Event`](../../../aspose.svg.dom.events/event/)-gränssnittet stöds av implementationen kommer denna metod att returnera ett nytt [`Event`](../../../aspose.svg.dom.events/event/) av den begärda gränssnittstypen. Om [`Event`](../../../aspose.svg.dom.events/event/) ska skickas via [`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/)-metoden måste den lämpliga [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/)-metoden anropas efter skapandet för att initiera värdena för [`Event`](../../../aspose.svg.dom.events/event/). |

### Returvärde

Det nyss skapade [`Event`](../../../aspose.svg.dom.events/event/)

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Uppstår om implementationen inte stöder den begärda typen av [`Event`](../../../aspose.svg.dom.events/event/)-gränssnitt |

### Se även

* class [Event](../../../aspose.svg.dom.events/event/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
