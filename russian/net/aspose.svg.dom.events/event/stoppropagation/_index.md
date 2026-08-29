---
title: "Event.StopPropagation"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Event StopPropagation. Метод StopPropagation используется для предотвращения дальнейшего распространения события во время потока событий."
type: docs
weight: 140
url: /ru/net/aspose.svg.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

Метод `StopPropagation` используется для предотвращения дальнейшего распространения события во время потока событий.

```csharp
public void StopPropagation()
```

## Замечания

Если этот метод вызывается любым [`IEventListener`](../../ieventlistener/), событие прекратит распространение по дереву. Событие завершит отправку всем слушателям на текущем [`IEventTarget`](../../ieventtarget/) до остановки потока событий. Этот метод может быть использован на любой стадии потока событий.

### См. также

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
