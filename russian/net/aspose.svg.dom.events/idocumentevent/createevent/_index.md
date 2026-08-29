---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод IDocumentEvent CreateEvent. Создает объект Event типа, поддерживаемого реализацией"
type: docs
weight: 10
url: /ru/net/aspose.svg.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Создает [`Event`](../../event/) типа, поддерживаемого реализацией.

```csharp
public Event CreateEvent(string eventType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | String | Параметр eventType указывает тип интерфейса [`Event`](../../event/), который необходимо создать. Если указанный интерфейс [`Event`](../../event/) поддерживается реализацией, этот метод вернёт новый [`Event`](../../event/) запрошенного типа интерфейса. Если [`Event`](../../event/) должен быть отправлен с помощью метода [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/), после создания необходимо вызвать соответствующий метод [`InitEvent`](../../event/initevent/) для инициализации значений [`Event`](../../event/). |

### Возвращаемое значение

Недавно созданный [`Event`](../../event/)

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает, если реализация не поддерживает запрошенный тип интерфейса [`Event`](../../event/) |

### См. также

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
