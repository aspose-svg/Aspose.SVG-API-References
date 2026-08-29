---
title: "Класс DocumentLoadErrorEvent"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Dom.Events.DocumentLoadErrorEvent. DocumentLoadErrorEvent возникает, когда запрашиваемый ресурс недоступен."
type: docs
weight: 2900
url: /ru/net/aspose.svg.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

Событие `DocumentLoadErrorEvent` возникает, когда запрашиваемый ресурс недоступен.

```csharp
public class DocumentLoadErrorEvent : ErrorEvent
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Используется для указания, является ли событие всплывающим. Если событие может всплывать, значение true, иначе false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Используется для указания, может ли действие события быть предотвращено. Если действие может быть предотвращено, значение true, иначе false. |
| [ColNo](../../aspose.svg.dom.events/errorevent/colno/) { get; } | Атрибут colno должен возвращать значение, с которым он был инициализирован. При создании объекта этот атрибут должен быть инициализирован нулём. Он представляет номер столбца, где в скрипте произошла ошибка. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Используется для указания [`IEventTarget`](../ieventtarget/), чьи [`IEventListener`](../ieventlistener/) в данный момент обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Возвращает true, если был вызван preventDefault() при значении атрибута cancelable, равном true, и false в противном случае. |
| [Error](../../aspose.svg.dom.events/errorevent/error/) { get; } | Атрибут error должен возвращать значение, к которому он был инициализирован. При создании объекта этот атрибут должен быть инициализирован значением null. При необходимости он устанавливается в объект, представляющий ошибку (например, объект исключения в случае необработанного исключения DOM). |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Используется для указания, какая фаза потока событий в данный момент оценивается. |
| [FileName](../../aspose.svg.dom.events/errorevent/filename/) { get; } | Атрибут filename должен возвращать значение, к которому он был инициализирован. При создании объекта этот атрибут должен быть инициализирован пустой строкой. Он представляет абсолютный URL скрипта, в котором изначально произошла ошибка. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Атрибут isTrusted должен возвращать значение, к которому он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [LineNo](../../aspose.svg.dom.events/errorevent/lineno/) { get; } | Атрибут lineno должен возвращать значение, к которому он был инициализирован. При создании объекта этот атрибут должен быть инициализирован нулём. Он представляет номер строки, где в скрипте произошла ошибка. |
| [Message](../../aspose.svg.dom.events/errorevent/message/) { get; } | Атрибут message должен возвращать значение, к которому он был инициализирован. При создании объекта этот атрибут должен быть инициализирован пустой строкой. Он представляет сообщение об ошибке. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Используется для указания [`IEventTarget`](../ieventtarget/), которому событие изначально было отправлено. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Используется для указания времени (в миллисекундах относительно эпохи), когда событие было создано. Поскольку некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть недоступно для некоторых событий. Если недоступно, будет возвращено значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 года. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Имя события (без учёта регистра). Имя должно быть XML‑именем. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Метод [`InitEvent`](../event/initevent/) используется для инициализации значения [`Event`](../event/), созданного через интерфейс [`IDocumentEvent`](../idocumentevent/). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Если событие отменяемо, метод [`PreventDefault`](../event/preventdefault/) используется для указания, что событие должно быть отменено, то есть любое действие по умолчанию, обычно выполняемое реализацией в результате события, не будет выполнено. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Вызов этого метода предотвращает доставку события к любым обработчикам, зарегистрированным после текущего, а при распространении в дереве также предотвращает доставку события к другим объектам. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Метод [`StopPropagation`](../event/stoppropagation/) используется для предотвращения дальнейшего распространения события во время потока событий. |

### См. также

* class [ErrorEvent](../errorevent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
