---
title: "IEventTarget.DispatchEvent"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод IEventTarget DispatchEvent. Этот метод позволяет отправлять события в модель событий реализации."
type: docs
weight: 20
url: /ru/net/aspose.svg.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Этот метод позволяет отправлять события в модель событий реализации.

```csharp
public bool DispatchEvent(Event @event)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| событие | Событие | Указывает тип события, его поведение и контекстную информацию, используемые при обработке события. |

### Возвращаемое значение

Возвращаемое значение [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) указывает, вызвали ли какие-либо обработчики, обработавшие событие, [`PreventDefault`](../../event/preventdefault/). Если [`PreventDefault`](../../event/preventdefault/) был вызван, значение равно false, в противном случае — true.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) |  |

## Замечания

События, отправленные таким образом, будут иметь такое же поведение захвата и всплытия, как события, отправляемые напрямую реализацией. Целевым объектом события является [`EventTarget`](../../../aspose.svg.dom/eventtarget/), на котором вызывается [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/).

### См. также

* class [Event](../../event/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
