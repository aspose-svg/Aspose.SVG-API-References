---
title: CustomEvent
second_title: Справочник по Aspose.SVG для .NET API
description: События использующие интерфейс CustomEvent могут использоваться для переноса пользовательских данных.
type: docs
weight: 890
url: /ru/net/aspose.svg.dom.events/customevent/
---
## CustomEvent class

События, использующие интерфейс CustomEvent, могут использоваться для переноса пользовательских данных.

```csharp
public class CustomEvent : Event
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CustomEvent](customevent#constructor)(string) | Инициализирует новый экземпляр класса[`CustomEvent`](../customevent). |
| [CustomEvent](customevent#constructor_1)(string, IDictionary&lt;string, object&gt;) | Инициализирует новый экземпляр класса[`CustomEvent`](../customevent). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles) { get; } | Используется, чтобы указать, является ли событие всплывающим событием. Если событие может всплыть, значение будет истинным, в противном случае значение будет ложным. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable) { get; } | Используется для указания того, можно ли предотвратить событие по умолчанию. Если действие по умолчанию можно предотвратить, значение равно true, в противном случае — значение false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget) { get; } | Используется для обозначения[`IEventTarget`](../ieventtarget), чей[`IEventListener`](../ieventlistener)в настоящее время обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented) { get; } | Возвращает true, если функция preventDefault() была вызвана, когда значение отменяемого атрибута равно true, и false в противном случае. |
| [Detail](../../aspose.svg.dom.events/customevent/detail) { get; } | Получает пользовательские данные. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase) { get; } | Используется для указания того, какая фаза потока событий оценивается в данный момент. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted) { get; } | Атрибут isTrusted должен возвращать значение, которым он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [Target](../../aspose.svg.dom.events/event/target) { get; } | Используется для указания[`IEventTarget`](../ieventtarget), на который изначально было отправлено событие. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp) { get; } | Используется для указания времени (в миллисекундах относительно эпохи), в которое было создано событие. В связи с тем, что некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть доступно не для всех событий. Если параметр недоступен, будет возвращено значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 года. |
| [Type](../../aspose.svg.dom.events/event/type) { get; } | Имя события (без учета регистра). Имя должно быть именем XML. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Этот метод используется для получения объекта ECMAScriptType. |
| [InitCustomEvent](../../aspose.svg.dom.events/customevent/initcustomevent)(string, bool, bool, object) | /// Используется метод[`InitEvent`](../event/initevent)для инициализации значения[`Event`](../event), созданного через интерфейс[`IDocumentEvent`](../idocumentevent). |
| [InitEvent](../../aspose.svg.dom.events/event/initevent)(string, bool, bool) | Метод[`InitEvent`](../event/initevent)используется для инициализации значение объекта[`Event`](../event), созданного через интерфейс [`IDocumentEvent`](../idocumentevent). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault)() | Если событие можно отменить, метод[`PreventDefault`](../event/preventdefault)используется для обозначения того, что событие должно быть отменено, означает, что никакие действия по умолчанию, обычно выполняемые реализацией в результате события, не будут выполняться. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation)() | Вызов этого метода не позволяет событию достичь каких-либо прослушивателей событий, зарегистрированных после текущего, а при отправке в дереве также предотвращает достижение события любыми другими объектами. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation)() | Метод[`StopPropagation`](../event/stoppropagation)используется для предотвращения дальнейшего распространения события во время потока событий. |

### Смотрите также

* class [Event](../event)
* пространство имен [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events)
* сборка [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
