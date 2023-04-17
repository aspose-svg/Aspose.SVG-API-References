---
title: TimeEvent.InitTimeEvent
second_title: Справочник по Aspose.SVG для .NET API
description: TimeEvent метод. Метод initTimeEvent используется для инициализации значения TimeEvent созданного через интерфейс DocumentEvent. Этот метод может быть вызван только до того как TimeEvent будет отправлен с помощью метода dispatchEvent хотя при необходимости он может вызываться несколько раз на этом этапе. При многократном вызове последний вызов имеет приоритет.
type: docs
weight: 30
url: /ru/net/aspose.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

Метод initTimeEvent используется для инициализации значения TimeEvent, созданного через интерфейс DocumentEvent. Этот метод может быть вызван только до того, как TimeEvent будет отправлен с помощью метода dispatchEvent, хотя при необходимости он может вызываться несколько раз на этом этапе. При многократном вызове последний вызов имеет приоритет.

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| typeArg | String | Указывает тип события. |
| viewArg | IAbstractView | Определяет AbstractView события. |
| detailArg | Int64 | Определяет детали события. |

### Смотрите также

* interface [IAbstractView](../../../aspose.svg.dom.views/iabstractview/)
* class [TimeEvent](../)
* пространство имен [Aspose.Svg.Events](../../timeevent/)
* сборка [Aspose.SVG](../../../)


