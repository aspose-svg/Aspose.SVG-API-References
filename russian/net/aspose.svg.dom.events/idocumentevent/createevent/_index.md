---
title: CreateEvent
second_title: Справочник по Aspose.SVG для .NET API
description: СоздаетEventaspose.svg.dom.events/eventтипа поддерживаемого реализацией.
type: docs
weight: 10
url: /ru/net/aspose.svg.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Создает[`Event`](../../event)типа, поддерживаемого реализацией.

```csharp
public Event CreateEvent(string eventType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | String | Параметр eventType указывает тип интерфейса[`Event`](../../event)для быть создан.  Если указанный интерфейс[`Event`](../../event)поддерживается реализацией, этот метод вернет новый [`Event`](../../event)запрошенного типа интерфейса. Если[`Event`](../../event)должен быть отправлен через[`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent)должен использоваться соответствующий метод [`InitEvent`](../../event/initevent). вызываться после создания для инициализации значений[`Event`](../../event). |

### Возвращаемое значение

Вновь созданный[`Event`](../../event)

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception) | NOT_SUPPORTED_ERR: Возникает, если реализация не поддерживает тип[`Event`](../../event)запрошен интерфейс |

### Смотрите также

* class [Event](../../event)
* interface [IDocumentEvent](../../idocumentevent)
* пространство имен [Aspose.Svg.Dom.Events](../../idocumentevent)
* сборка [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->