---
title: "Aspose.Svg.Dom.Events"
second_title: "Aspose.SVG для .NET справочник API"
description: "Пространство имен Aspose.Svg.Dom.Events предоставляет объекты для любых событий, связанных с обновлением DOM. Оно включает подписку на наблюдение за конкретной контекстной информацией, связанной с событием, а также создание пользовательских событий."
type: docs
weight: 100
url: /ru/net/aspose.svg.dom.events/
---
Пространство имён **Aspose.Svg.Dom.Events** предоставляет объекты для любых событий, связанных с обновлением DOM. Оно включает подписку на наблюдение за конкретной контекстной информацией, связанной с событием, а также создание пользовательских событий.

## Классы

| Класс | Описание |
| --- | --- |
| [CustomEvent](./customevent/) | События, использующие интерфейс CustomEvent, могут использоваться для передачи пользовательских данных. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | Событие [`DocumentLoadErrorEvent`](../aspose.svg.dom.events/documentloaderrorevent/) происходит, когда запрашиваемый ресурс недоступен. |
| [DOMEventHandler](./domeventhandler/) | Представляет обратный вызов для обработки событий. |
| [ErrorEvent](./errorevent/) | Событие [`ErrorEvent`](../aspose.svg.dom.events/errorevent/) предоставляет контекстную информацию об ошибках, возникших во время выполнения. |
| [Event](./event/) | Событие [`Event`](../aspose.svg.dom.events/event/) используется для предоставления контекстной информации о событии обработчику, который обрабатывает событие. |
| [FocusEvent](./focusevent/) | Интерфейс FocusEvent предоставляет специфическую контекстную информацию, связанную с событиями фокуса. |
| [InputEvent](./inputevent/) | События ввода отправляются в виде уведомлений каждый раз, когда DOM обновляется. |
| [KeyboardEvent](./keyboardevent/) | Интерфейс KeyboardEvent предоставляет специфическую контекстную информацию, связанную с клавиатурными устройствами. Каждое клавиатурное событие ссылается на клавишу с помощью значения. Клавиатурные события обычно направлены на элемент, имеющий фокус. |
| [MouseEvent](./mouseevent/) | Интерфейс MouseEvent предоставляет специфическую контекстную информацию, связанную с событиями мыши. |
| [UIEvent](./uievent/) | Интерфейс UIEvent предоставляет специфическую контекстную информацию, связанную с событиями пользовательского интерфейса. |
| [WheelEvent](./wheelevent/) | Интерфейс WheelEvent предоставляет специфическую контекстную информацию, связанную с событиями колесика. Чтобы создать экземпляр интерфейса WheelEvent, используйте конструктор WheelEvent, передавая необязательный словарь WheelEventInit. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | Интерфейс [`IDocumentEvent`](../aspose.svg.dom.events/idocumentevent/) предоставляет механизм, с помощью которого пользователь может создать [`Event`](../aspose.svg.dom.events/event/) поддерживаемого типа реализации. |
| [IEventListener](./ieventlistener/) | The interface [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) является основным способом обработки событий. Пользователи реализуют интерфейс [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) и регистрируют свой слушатель на [`EventTarget`](../aspose.svg.dom/eventtarget/) с помощью метода [`AddEventListener`](../aspose.svg.dom/eventtarget/addeventlistener/). Пользователи также должны удалить свой [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) из соответствующего [`EventTarget`](../aspose.svg.dom/eventtarget/) после того как завершат использование слушателя. |
| [IEventTarget](./ieventtarget/) | The interface [`EventTarget`](../aspose.svg.dom/eventtarget/) реализуется всеми узлами в реализации, поддерживающей модель событий DOM. Поэтому этот интерфейс можно получить, используя методы привязочного приведения типов к экземпляру интерфейса Node. Интерфейс позволяет регистрировать и удалять обработчики событий на [`EventTarget`](../aspose.svg.dom/eventtarget/) и отправлять события этому [`IEventTarget`](../aspose.svg.dom.events/ieventtarget/). |
