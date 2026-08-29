---
title: "CustomEvent.InitCustomEvent"
second_title: "Aspose.SVG для .NET справочник API"
description: "CustomEvent InitCustomEvent method. /// Метод InitEvent используется для инициализации значения события, созданного через интерфейс IDocumentEvent"
type: docs
weight: 30
url: /ru/net/aspose.svg.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Метод [`InitEvent`](../../event/initevent/) используется для инициализации значения [`Event`](../../event/), созданного через интерфейс [`IDocumentEvent`](../../idocumentevent/).

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Тип события. |
| bubbles | Boolean | если установлено `true` [bubbles]. |
| cancelable | Boolean | если установлено `true` [cancelable]. |
| detail | Объект | Пользовательские данные. |

## Замечания

Этот метод может быть вызван только до того, как событие будет отправлено с помощью метода [`DispatchEvent`](../../ieventtarget/dispatchevent/), хотя при необходимости его можно вызвать несколько раз в течение этой фазы. При множественных вызовах приоритет имеет последнее вызов. Если метод вызывается из подкласса интерфейса Event, изменяются только значения, указанные в методе initEvent, все остальные атрибуты остаются без изменений.

### См. также

* class [CustomEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
