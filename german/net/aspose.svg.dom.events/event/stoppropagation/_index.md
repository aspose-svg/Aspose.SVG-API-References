---
title: "Event.StopPropagation"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Event StopPropagation-Methode. Die StopPropagation-Methode wird verwendet, um die weitere Weiterleitung eines Ereignisses während des Ereignisflusses zu verhindern."
type: docs
weight: 140
url: /de/net/aspose.svg.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

Die `StopPropagation`-Methode wird verwendet, um die weitere Weiterleitung eines Ereignisses während des Ereignisflusses zu verhindern.

```csharp
public void StopPropagation()
```

## Hinweise

Wenn diese Methode von einem beliebigen [`IEventListener`](../../ieventlistener/) aufgerufen wird, hört das Ereignis auf, durch den Baum zu propagieren. Das Ereignis wird die Zustellung an alle Listener des aktuellen [`IEventTarget`](../../ieventtarget/) abschließen, bevor der Ereignisfluss stoppt. Diese Methode kann in jeder Phase des Ereignisflusses verwendet werden.

### Siehe auch

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
