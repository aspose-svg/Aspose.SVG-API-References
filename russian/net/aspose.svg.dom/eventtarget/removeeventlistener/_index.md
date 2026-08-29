---
title: "EventTarget.RemoveEventListener"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод EventTarget RemoveEventListener. Этот метод позволяет удалять обработчики событий из целевого объекта. Если IEventListener удаляется из EventTarget во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после удаления."
type: docs
weight: 50
url: /ru/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#removeeventlistener}

Этот метод позволяет удалять обработчики событий из целевого объекта. Если [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после удаления.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Указывает тип события [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/), который удаляется. |
| handler | DOMEventHandler | Параметр [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) указывает [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/), который будет удалён. |
| useCapture | Boolean | Указывает, был ли удаляемый EventListener зарегистрирован как захватывающий обработчик или нет. Если обработчик был зарегистрирован дважды, один с захватом и один без, каждый из них необходимо удалять отдельно. Удаление захватывающего обработчика не влияет на незахватывающую версию того же обработчика и наоборот. |

### См. также

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#removeeventlistener_1}

Этот метод позволяет удалять обработчики событий из целевого объекта. Если [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после удаления.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Указывает тип события [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/), который удаляется. |
| listener | IEventListener | Параметр [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) указывает на [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/), который будет удалён. |

### См. также

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#removeeventlistener_2}

Этот метод позволяет удалять обработчики событий из целевого объекта. Если [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) удаляется из [`EventTarget`](../) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после удаления.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Указывает тип события [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/), который удаляется. |
| listener | IEventListener | Параметр [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) указывает на [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/), который будет удалён. |
| useCapture | Boolean | Указывает, был ли удаляемый EventListener зарегистрирован как захватывающий обработчик или нет. Если обработчик был зарегистрирован дважды, один с захватом и один без, каждый из них необходимо удалять отдельно. Удаление захватывающего обработчика не влияет на незахватывающую версию того же обработчика и наоборот. |

### См. также

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
