---
title: "IEventTarget.RemoveEventListener"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод IEventTarget RemoveEventListener. Этот метод позволяет удалять обработчики событий из целевого объекта события. Если IEventListener удаляется из EventTarget во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после удаления."
type: docs
weight: 30
url: /ru/net/aspose.svg.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [IEventListener](../../ieventlistener/)*) {#removeeventlistener}

Этот метод позволяет удалять обработчики событий из целевого объекта события. Если [`IEventListener`](../../ieventlistener/) удаляется из [`EventTarget`](../../../aspose.svg.dom/eventtarget/) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после удаления.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Указывает тип события у удаляемого [`IEventListener`](../../ieventlistener/). |
| listener | IEventListener | Параметр [`IEventListener`](../../ieventlistener/) указывает, какой [`IEventListener`](../../ieventlistener/) следует удалить. |

### См. также

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#removeeventlistener_1}

Этот метод позволяет удалять обработчики событий из целевого объекта события. Если [`IEventListener`](../../ieventlistener/) удаляется из [`EventTarget`](../../../aspose.svg.dom/eventtarget/) во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после удаления.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Указывает тип события у удаляемого [`IEventListener`](../../ieventlistener/). |
| listener | IEventListener | Параметр [`IEventListener`](../../ieventlistener/) указывает, какой [`IEventListener`](../../ieventlistener/) следует удалить. |
| useCapture | Boolean | Указывает, был ли удаляемый EventListener зарегистрирован как захватывающий обработчик или нет. Если обработчик был зарегистрирован дважды, один с захватом и один без, каждый из них необходимо удалять отдельно. Удаление захватывающего обработчика не влияет на незахватывающую версию того же обработчика и наоборот. |

### См. также

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
