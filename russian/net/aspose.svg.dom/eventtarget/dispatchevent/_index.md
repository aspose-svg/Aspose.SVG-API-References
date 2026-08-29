---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод EventTarget DispatchEvent. Синхронно отправляет событие указанному IEventTarget, вызывая затронутые EventListeners в правильном порядке. Обычные правила обработки событий, включая фазу захвата и необязательную фазу всплытия, также применяются к событиям, отправленным вручную с помощью DispatchEvent."
type: docs
weight: 30
url: /ru/net/aspose.svg.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Отправляет событие указанному [`IEventTarget`](../../../aspose.svg.dom.events/ieventtarget/), (синхронно) вызывая затронутые EventListeners в правильном порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправленным вручную с помощью [`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/).

```csharp
public bool DispatchEvent(Event @event)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| событие | Событие | Указывает тип события, его поведение и контекстную информацию, используемые при обработке события. |

### Возвращаемое значение

Возвращаемое значение `DispatchEvent` указывает, вызвал ли какой‑либо из обработчиков, обработавших событие, [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/). Если [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/) был вызван, значение равно false, иначе значение равно true.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception/) |  |

## Замечания

События, отправленные таким образом, будут иметь такое же поведение захвата и всплытия, как события, отправленные напрямую реализацией. Целевым объектом события является [`EventTarget`](../), на котором вызывается `DispatchEvent`.

### См. также

* class [Event](../../../aspose.svg.dom.events/event/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
