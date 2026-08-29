---
title: "TimeEvent.InitTimeEvent"
second_title: "Aspose.SVG для .NET справочник API"
description: "TimeEvent InitTimeEvent метод. Метод initTimeEvent используется для инициализации значения TimeEvent, созданного через интерфейс DocumentEvent. Этот метод может быть вызван только до того, как TimeEvent будет отправлен через метод dispatchEvent, хотя при необходимости его можно вызвать несколько раз в течение этой фазы. Если вызвать его несколько раз, последующий вызов имеет приоритет."
type: docs
weight: 30
url: /ru/net/aspose.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

Метод initTimeEvent используется для инициализации значения TimeEvent, созданного через интерфейс DocumentEvent. Этот метод может быть вызван только до того, как TimeEvent будет отправлен с помощью метода dispatchEvent, хотя при необходимости его можно вызвать несколько раз в этом этапе. Если вызвано несколько раз, приоритет имеет последний вызов.

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| typeArg | String | Указывает тип события. |
| viewArg | IAbstractView | Указывает AbstractView события. |
| detailArg | Int64 | Указывает detail события. |

### См. также

* interface [IAbstractView](../../../aspose.svg.dom.views/iabstractview/)
* class [TimeEvent](../)
* namespace [Aspose.Svg.Events](../../../aspose.svg.events/)
* assembly [Aspose.SVG](../../../)
