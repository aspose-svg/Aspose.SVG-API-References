---
title: "Класс Event"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Dom.Events.Event. Событие используется для предоставления контекстной информации о событии обработчику, который обрабатывает событие"
type: docs
weight: 2920
url: /ru/net/aspose.svg.dom.events/event/
---
## Event class

Событие `Event` используется для предоставления контекстной информации о событии обработчику, который обрабатывает событие.

```csharp
public class Event : DOMObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Event](event/#constructor)(*string*) | Инициализирует новый экземпляр класса `Event`. |
| [Event](event/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Инициализирует новый экземпляр класса `Event`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Используется для указания, является ли событие всплывающим. Если событие может всплывать, значение true, иначе false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Используется для указания, может ли действие события быть предотвращено. Если действие может быть предотвращено, значение true, иначе false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Используется для указания [`IEventTarget`](../ieventtarget/), чьи [`IEventListener`](../ieventlistener/) в данный момент обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Возвращает true, если был вызван preventDefault() при значении атрибута cancelable, равном true, и false в противном случае. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Используется для указания, какая фаза потока событий в данный момент оценивается. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Атрибут isTrusted должен возвращать значение, к которому он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Используется для указания [`IEventTarget`](../ieventtarget/), которому событие изначально было отправлено. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Используется для указания времени (в миллисекундах относительно эпохи), когда событие было создано. Поскольку некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть недоступно для некоторых событий. Если недоступно, будет возвращено значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 года. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Имя события (без учёта регистра). Имя должно быть XML‑именем. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Метод [`InitEvent`](./initevent/) используется для инициализации значения `Event`, созданного через интерфейс [`IDocumentEvent`](../idocumentevent/). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Если событие отменяемо, метод [`PreventDefault`](./preventdefault/) используется для указания, что событие должно быть отменено, что означает, что любое действие по умолчанию, обычно выполняемое реализацией в результате события, не произойдёт. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Вызов этого метода предотвращает доставку события к любым обработчикам, зарегистрированным после текущего, а при распространении в дереве также предотвращает доставку события к другим объектам. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Метод [`StopPropagation`](./stoppropagation/) используется для предотвращения дальнейшего распространения события во время потока событий. |

## Поля

| Имя | Описание |
| --- | --- |
| const [AtTargetPhase](../../aspose.svg.dom.events/event/attargetphase/) | Текущая фаза события — фаза захвата. |
| const [BubblingPhase](../../aspose.svg.dom.events/event/bubblingphase/) | Текущая фаза события — фаза всплытия. |
| const [CapturingPhase](../../aspose.svg.dom.events/event/capturingphase/) | Событие в данный момент оценивается у целевого [`IEventTarget`](../ieventtarget/). |
| const [NonePhase](../../aspose.svg.dom.events/event/nonephase/) | События, которые в данный момент не отправляются, находятся в этой фазе. |

## Замечания

Объект, реализующий `Event`, обычно передаётся в качестве первого параметра обработчику события. Более конкретная контекстная информация передаётся обработчикам событий путём создания дополнительных интерфейсов, наследуемых от `Event`, которые содержат сведения, непосредственно относящиеся к типу сопровождающего их события. Эти производные интерфейсы также реализуются объектом, передаваемым слушателю события.

### См. также

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
