---
title: "Event.PreventDefault"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Event PreventDefault-Methode. Wenn ein Ereignis abbrechbar ist, wird die PreventDefault-Methode verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, was bedeutet, dass jede Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses durchgeführt wird, nicht erfolgt."
type: docs
weight: 120
url: /de/net/aspose.svg.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Wenn ein Ereignis abbrechbar ist, wird die `PreventDefault`-Methode verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, was bedeutet, dass jede Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses durchgeführt wird, nicht erfolgt.

```csharp
public void PreventDefault()
```

## Hinweise

Wenn während irgendeiner Phase des Ereignisflusses die `PreventDefault`-Methode aufgerufen wird, wird das Ereignis abgebrochen. Jede mit dem Ereignis verbundene Standardaktion wird nicht ausgeführt. Das Aufrufen dieser Methode für ein nicht abbrechbares Ereignis hat keine Wirkung. Sobald `PreventDefault` aufgerufen wurde, bleibt es für den Rest der Ereignispropagation wirksam. Diese Methode kann in jeder Phase des Ereignisflusses verwendet werden.

### Siehe auch

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
