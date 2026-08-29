---
title: "Класс MediaQueryList"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Window.MediaQueryList. Объект MediaQueryList хранит информацию о медиазапросе, применённом к документу, с поддержкой как немедленного, так и событийно‑ориентированного сопоставления с состоянием документа. См. спецификацию CSSOM View Module https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /ru/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

Объект MediaQueryList хранит информацию о медиазапросе, применённом к документу, с поддержкой как немедленного, так и событийного сопоставления с состоянием документа. См. спецификацию модуля CSSOM View: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | Документ, связанный с объектом Context. |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | Булево значение, которое возвращает true, если документ в данный момент соответствует списку медиазапросов, или false в противном случае. |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | Строка, представляющая сериализованный медиазапрос. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Добавить слушатель события изменения состояния matches у MediaQueryList. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Отправляет событие Event указанному [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (синхронно) вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправляемым вручную с помощью [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Этот метод позволяет удалять слушатели событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../../aspose.svg.dom/eventtarget/) во время обработки события, он не будет вызван текущими действиями. Слушатели событий никогда не могут быть вызваны после их удаления. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Этот метод позволяет удалять слушатели событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../../aspose.svg.dom/eventtarget/) во время обработки события, он не будет вызван текущими действиями. Слушатели событий никогда не могут быть вызваны после их удаления. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Этот метод позволяет удалять слушатели событий из цели события. Если [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../../aspose.svg.dom/eventtarget/) во время обработки события, он не будет вызван текущими действиями. Слушатели событий никогда не могут быть вызваны после их удаления. |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Удалить слушатель события изменения состояния matches у MediaQueryList. |

## События

| Имя | Описание |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | Событие, которое генерируется у MediaQueryList при изменении состояния matches. |

### См. также

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
