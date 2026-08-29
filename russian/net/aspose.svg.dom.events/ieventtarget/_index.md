---
title: "Интерфейс IEventTarget"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Dom.Events.IEventTarget. Интерфейс EventTarget реализуется всеми объектами Node в реализации, поддерживающей модель событий DOM. Поэтому этот интерфейс можно получить, используя методы привязочного приведения типов к экземпляру интерфейса Node. Интерфейс позволяет регистрировать и удалять слушатели событий на объекте EventTarget и отправлять события этому IEventTarget."
type: docs
weight: 2960
url: /ru/net/aspose.svg.dom.events/ieventtarget/
---
## IEventTarget interface

Интерфейс [`EventTarget`](../../aspose.svg.dom/eventtarget/) реализуется всеми узлами в реализации, поддерживающей модель событий DOM. Поэтому этот интерфейс можно получить, используя методы привязочного приведения типов к экземпляру интерфейса Node. Интерфейс позволяет регистрировать и удалять обработчики событий на [`EventTarget`](../../aspose.svg.dom/eventtarget/) и отправлять события этому `IEventTarget`.

```csharp
public interface IEventTarget
```

## Методы

| Имя | Описание |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener)(*string, [IEventListener](../ieventlistener/)*) | Этот метод позволяет регистрировать обработчики событий на целевом объекте события. |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | Этот метод позволяет регистрировать обработчики событий на целевом объекте события. |
| [DispatchEvent](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)(*[Event](../event/)*) | Этот метод позволяет отправлять события в модель событий реализации. |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(*string, [IEventListener](../ieventlistener/)*) | Этот метод позволяет удалять обработчики событий с целевого объекта события. Если [`IEventListener`](../ieventlistener/) удаляется из [`EventTarget`](../../aspose.svg.dom/eventtarget/) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | Этот метод позволяет удалять обработчики событий с целевого объекта события. Если [`IEventListener`](../ieventlistener/) удаляется из [`EventTarget`](../../aspose.svg.dom/eventtarget/) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |

### См. также

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
