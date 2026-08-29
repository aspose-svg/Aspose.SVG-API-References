---
title: "Document.CreateEvent"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Document CreateEvent. Создает объект Event типа, поддерживаемого реализацией"
type: docs
weight: 880
url: /ru/net/aspose.svg.dom/document/createevent/
---
## Document.CreateEvent method

Создает [`Event`](../../../aspose.svg.dom.events/event/) типа, поддерживаемого реализацией.

```csharp
public Event CreateEvent(string eventType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | String | Параметр eventType указывает тип интерфейса [`Event`](../../../aspose.svg.dom.events/event/) для создания. Если указанный интерфейс [`Event`](../../../aspose.svg.dom.events/event/) поддерживается реализацией, этот метод вернёт новый объект [`Event`](../../../aspose.svg.dom.events/event/) запрошенного типа интерфейса. Если объект [`Event`](../../../aspose.svg.dom.events/event/) должен быть отправлен через метод [`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/), после создания необходимо вызвать соответствующий метод [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/), чтобы инициализировать значения объекта [`Event`](../../../aspose.svg.dom.events/event/). |

### Возвращаемое значение

Недавно созданный [`Event`](../../../aspose.svg.dom.events/event/)

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если реализация не поддерживает запрошенный тип интерфейса [`Event`](../../../aspose.svg.dom.events/event/) |

### См. также

* class [Event](../../../aspose.svg.dom.events/event/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
