---
title: "SVGSVGElement.CreateEvent"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGSVGElement CreateEvent. Создаёт объект Event указанного типа, поддерживаемого реализацией."
type: docs
weight: 110
url: /ru/net/aspose.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Создает [`Event`](../../../aspose.svg.dom.events/event/) типа, поддерживаемого реализацией.

```csharp
public Event CreateEvent(string eventType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | String | Параметр eventType указывает тип интерфейса [`Event`](../../../aspose.svg.dom.events/event/), который необходимо создать. Если указанный интерфейс [`Event`](../../../aspose.svg.dom.events/event/) поддерживается реализацией, этот метод вернёт новый [`Event`](../../../aspose.svg.dom.events/event/) запрошенного типа. Если [`Event`](../../../aspose.svg.dom.events/event/) должен быть отправлен через метод [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/), после создания необходимо вызвать соответствующий метод [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/), чтобы инициализировать значения [`Event`](../../../aspose.svg.dom.events/event/). |

### Возвращаемое значение

Недавно созданный [`Event`](../../../aspose.svg.dom.events/event/)

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает, если реализация не поддерживает запрошенный тип интерфейса [`Event`](../../../aspose.svg.dom.events/event/) |

### См. также

* class [Event](../../../aspose.svg.dom.events/event/)
* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
