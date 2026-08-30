---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.SVG för .NET API-referens"
description: "IDocumentEvent CreateEvent‑metod. Skapar en Event av en typ som stöds av implementationen."
type: docs
weight: 10
url: /sv/net/aspose.svg.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Skapar ett [`Event`](../../event/) av en typ som stöds av implementationen.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | String | Parametern eventType specificerar vilken typ av [`Event`](../../event/)‑gränssnitt som ska skapas. Om det angivna [`Event`](../../event/)‑gränssnittet stöds av implementationen kommer denna metod att returnera ett nytt [`Event`](../../event/) av den begärda gränssnittstypen. Om [`Event`](../../event/) ska skickas via metoden [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) måste den lämpliga metoden [`InitEvent`](../../event/initevent/) anropas efter skapandet för att initiera värdena för [`Event`](../../event/). |

### Returvärde

Det nyss skapade [`Event`](../../event/)

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Uppstår om implementationen inte stöder den begärda typen av [`Event`](../../event/)‑gränssnitt. |

### Se även

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
