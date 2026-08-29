---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод IEventTarget AddEventListener. Этот метод позволяет регистрировать обработчики событий на целевом объекте события."
type: docs
weight: 10
url: /ru/net/aspose.svg.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(*string, [IEventListener](../../ieventlistener/)*) {#addeventlistener}

Этот метод позволяет регистрировать обработчики событий на целевом объекте события.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Тип события, для которого пользователь регистрирует обработчик. |
| слушатель | IEventListener | Принимает интерфейс, реализованный пользователем, который содержит методы, вызываемые при возникновении события. |

## Замечания

Если [`IEventListener`](../../ieventlistener/) добавляется в [`EventTarget`](../../../aspose.svg.dom/eventtarget/) во время обработки события, он не будет вызван текущими действиями, но может быть вызван на более поздней стадии потока событий, например, на фазе всплытия.

Если несколько одинаковых обработчиков событий зарегистрированы на одном и том же [`EventTarget`](../../../aspose.svg.dom/eventtarget/) с одинаковыми параметрами, дублирующие экземпляры отбрасываются. Они не вызывают двойного вызова [`IEventListener`](../../ieventlistener/), и поскольку отбрасываются, их не нужно удалять с помощью метода [`RemoveEventListener`](../removeeventlistener/).

### См. также

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#addeventlistener_1}

Этот метод позволяет регистрировать обработчики событий на целевом объекте события.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | String | Тип события, для которого пользователь регистрирует обработчик. |
| слушатель | IEventListener | Принимает интерфейс, реализованный пользователем, который содержит методы, вызываемые при возникновении события. |
| useCapture | Boolean | Если true, useCapture указывает, что пользователь хочет инициировать захват. После инициации захвата все события указанного типа будут отправлены зарегистрированному [`IEventListener`](../../ieventlistener/) до того, как они будут отправлены любым целевым объектам событий ниже их в дереве. События, поднимающиеся вверх по дереву, не будут вызывать [`IEventListener`](../../ieventlistener/), назначенный для использования захвата. |

## Замечания

Если [`IEventListener`](../../ieventlistener/) добавляется в [`EventTarget`](../../../aspose.svg.dom/eventtarget/) во время обработки события, он не будет вызван текущими действиями, но может быть вызван на более поздней стадии потока событий, например, на фазе всплытия.

Если несколько одинаковых обработчиков событий зарегистрированы на одном и том же [`EventTarget`](../../../aspose.svg.dom/eventtarget/) с одинаковыми параметрами, дублирующие экземпляры отбрасываются. Они не вызывают двойного вызова [`IEventListener`](../../ieventlistener/), и поскольку отбрасываются, их не нужно удалять с помощью метода [`RemoveEventListener`](../removeeventlistener/).

### См. также

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
