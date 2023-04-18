---
title: EventTarget.RemoveEventListener
second_title: .NET API 참조용 Aspose.SVG
description: EventTarget 방법. 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. IEventListener 에서 제거됩니다.EventTarget 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다.
type: docs
weight: 40
url: /ko/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 에서 제거됩니다.[`EventTarget`](../) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| type | String | 의 이벤트 유형을 지정합니다.[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 제거 중입니다. |
| handler | DOMEventHandler | 그만큼[`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) 매개변수는[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 제거할 수 있습니다. |
| useCapture | Boolean | 제거 중인 EventListener가 캡처 리스너로 등록되었는지 여부를 지정합니다. 리스너가 캡처가 있는 경우와 없는 경우 두 번 등록된 경우 각각 별도로 제거해야 합니다. 캡처 중인 리스너를 제거해도 캡처하지 않는 버전에는 영향을 미치지 않습니다. 같은 리스너의 경우, 그 반대의 경우도 마찬가지입니다. |

### 또한보십시오

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* 네임스페이스 [Aspose.Svg.Dom](../../eventtarget/)
* 집회 [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 에서 제거됩니다.[`EventTarget`](../) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| type | String | 의 이벤트 유형을 지정합니다.[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 제거 중입니다. |
| listener | IEventListener | 그만큼[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 매개변수는[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 제거할 수 있습니다. |

### 또한보십시오

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* 네임스페이스 [Aspose.Svg.Dom](../../eventtarget/)
* 집회 [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 에서 제거됩니다.[`EventTarget`](../) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| type | String | 의 이벤트 유형을 지정합니다.[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 제거 중입니다. |
| listener | IEventListener | 그만큼[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 매개변수는[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) 제거할 수 있습니다. |
| useCapture | Boolean | 제거 중인 EventListener가 캡처 리스너로 등록되었는지 여부를 지정합니다. 리스너가 캡처가 있는 경우와 없는 경우 두 번 등록된 경우 각각 별도로 제거해야 합니다. 캡처 중인 리스너를 제거해도 캡처하지 않는 버전에는 영향을 미치지 않습니다. 같은 리스너의 경우, 그 반대의 경우도 마찬가지입니다. |

### 또한보십시오

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* 네임스페이스 [Aspose.Svg.Dom](../../eventtarget/)
* 집회 [Aspose.SVG](../../../)


