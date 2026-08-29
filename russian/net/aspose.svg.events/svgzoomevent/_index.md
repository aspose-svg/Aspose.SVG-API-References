---
title: "Класс SVGZoomEvent"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Events.SVGZoomEvent. Событие масштабирования происходит, когда пользователь инициирует действие, вызывающее изменение масштаба текущего представления фрагмента SVG‑документа. Обработчики событий распознаются только на элементах svg."
type: docs
weight: 3710
url: /ru/net/aspose.svg.events/svgzoomevent/
---
## SVGZoomEvent class

Событие масштабирования происходит, когда пользователь инициирует действие, которое приводит к изменению масштаба текущего представления фрагмента SVG‑документа. Обработчики событий распознаются только на элементах ‘svg’.

```csharp
public class SVGZoomEvent : Event
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Используется для указания, является ли событие всплывающим. Если событие может всплывать, значение true, иначе false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Используется для указания, может ли действие события быть предотвращено. Если действие может быть предотвращено, значение true, иначе false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Используется для указания [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), чьи [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) в данный момент обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Возвращает true, если был вызван preventDefault() при значении атрибута cancelable, равном true, и false в противном случае. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Используется для указания, какая фаза потока событий в данный момент оценивается. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Атрибут isTrusted должен возвращать значение, к которому он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [NewScale](../../aspose.svg.events/svgzoomevent/newscale/) { get; } | Коэффициент масштабирования, который будет установлен после обработки операции масштабирования. |
| [NewTranslate](../../aspose.svg.events/svgzoomevent/newtranslate/) { get; } | Значения трансляции, которые будут установлены после обработки операции масштабирования. Объект SVGPoint доступен только для чтения. |
| [PreviousScale](../../aspose.svg.events/svgzoomevent/previousscale/) { get; } | Коэффициент масштабирования из предыдущих операций масштабирования, который был установлен до начала текущей операции. |
| [PreviousTranslate](../../aspose.svg.events/svgzoomevent/previoustranslate/) { get; } | Значения трансляции из предыдущих операций масштабирования, которые были установлены до начала текущей операции. Объект SVGPoint доступен только для чтения. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Используется для указания [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), к которому событие изначально было отправлено. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Используется для указания времени (в миллисекундах относительно эпохи), когда событие было создано. Поскольку некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть недоступно для некоторых событий. Если недоступно, будет возвращено значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 года. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Имя события (без учёта регистра). Имя должно быть XML‑именем. |
| [ZoomRectScreen](../../aspose.svg.events/svgzoomevent/zoomrectscreen/) { get; } | Указанный прямоугольник масштабирования в единицах экрана. Объект SVGRect доступен только для чтения. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Метод [`InitEvent`](../../aspose.svg.dom.events/event/initevent/) используется для инициализации значения [`Event`](../../aspose.svg.dom.events/event/), созданного через интерфейс [`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Если событие отменяемо, метод [`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/) используется для указания, что событие должно быть отменено, что означает, что любое действие по умолчанию, обычно выполняемое реализацией в результате события, не произойдёт. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Вызов этого метода предотвращает доставку события к любым обработчикам, зарегистрированным после текущего, а при распространении в дереве также предотвращает доставку события к другим объектам. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Метод [`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/) используется для предотвращения дальнейшего распространения события во время его потока. |

### См. также

* class [Event](../../aspose.svg.dom.events/event/)
* namespace [Aspose.Svg.Events](../../aspose.svg.events/)
* assembly [Aspose.SVG](../../)
