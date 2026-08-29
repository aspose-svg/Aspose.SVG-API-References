---
title: "Интерфейс IEventListener"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Dom.Events.IEventListener. Интерфейс IEventListener является основным способом обработки событий. Пользователи реализуют интерфейс IEventListener и регистрируют свой слушатель на объекте EventTarget, используя метод AddEventListener. Пользователи также должны удалить свой IEventListener из его EventTarget после завершения использования слушателя."
type: docs
weight: 2950
url: /ru/net/aspose.svg.dom.events/ieventlistener/
---
## IEventListener interface

Интерфейс `IEventListener` является основным способом обработки событий. Пользователи реализуют интерфейс `IEventListener` и регистрируют свой слушатель на [`EventTarget`](../../aspose.svg.dom/eventtarget/) с помощью метода [`AddEventListener`](../../aspose.svg.dom/eventtarget/addeventlistener/). Пользователи также должны удалить свой `IEventListener` из его [`EventTarget`](../../aspose.svg.dom/eventtarget/) после завершения использования слушателя.

```csharp
public interface IEventListener
```

## Методы

| Имя | Описание |
| --- | --- |
| [HandleEvent](../../aspose.svg.dom.events/ieventlistener/handleevent/)(*[Event](../event/)*) | Этот метод вызывается каждый раз, когда происходит событие типа, для которого был зарегистрирован интерфейс `IEventListener`. |

## Замечания

При копировании узла (Node) с помощью метода cloneNode обработчики событий, прикреплённые к исходному узлу, не прикрепляются к скопированному узлу. Если пользователь хочет, чтобы те же обработчики событий были добавлены к вновь созданной копии, пользователь должен добавить их вручную.

### См. также

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
