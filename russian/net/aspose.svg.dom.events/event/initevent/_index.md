---
title: "Event.InitEvent"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Event InitEvent. Метод InitEvent используется для инициализации значения события, созданного через интерфейс IDocumentEvent."
type: docs
weight: 110
url: /ru/net/aspose.svg.dom.events/event/initevent/
---
## Event.InitEvent method

Метод `InitEvent` используется для инициализации значения [`Event`](../), созданного через интерфейс [`IDocumentEvent`](../../idocumentevent/).

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Тип события. |
| bubbles | Boolean | если установлено `true` [bubbles]. |
| cancelable | Boolean | если установлено `true` [cancelable]. |

## Замечания

Этот метод может быть вызван только до того, как событие будет отправлено с помощью метода [`DispatchEvent`](../../ieventtarget/dispatchevent/), хотя при необходимости его можно вызвать несколько раз в течение этой фазы. При множественных вызовах приоритет имеет последнее вызов. Если метод вызывается из подкласса интерфейса Event, изменяются только значения, указанные в методе initEvent, все остальные атрибуты остаются без изменений.

### См. также

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
