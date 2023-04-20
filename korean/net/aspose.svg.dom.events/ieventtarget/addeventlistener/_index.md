---
title: IEventTarget.AddEventListener
second_title: .NET API 참조용 Aspose.SVG
description: IEventTarget 방법. 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다.
type: docs
weight: 10
url: /ko/net/aspose.svg.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(string, IEventListener) {#addeventlistener}

이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| type | String | 사용자가 등록하는 이벤트 유형 |
| listener | IEventListener | 이벤트가 발생할 때 호출할 메서드를 포함하는 사용자가 구현한 인터페이스를 사용합니다. |

### 비고

경우[`IEventListener`](../../ieventlistener/) 에 추가됩니다[`EventTarget`](../../../aspose.svg.dom/eventtarget/) 이벤트를 처리하는 동안 현재 작업에 의해 트리거 되지 않지만 버블링 단계와 같은 이벤트 흐름의 이후 단계에서 트리거될 수 있습니다.

동일한 이벤트 리스너가 여러 개 등록된 경우[`EventTarget`](../../../aspose.svg.dom/eventtarget/)동일한 매개변수를 사용하면 중복 인스턴스가 삭제됩니다. [`IEventListener`](../../ieventlistener/) 두 번 호출되고 폐기되기 때문에 the 로 제거할 필요가 없습니다.[`RemoveEventListener`](../removeeventlistener/) 방법.

### 또한보십시오

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* 네임스페이스 [Aspose.Svg.Dom.Events](../../ieventtarget/)
* 집회 [Aspose.SVG](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_1}

이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| type | String | 사용자가 등록하는 이벤트 유형 |
| listener | IEventListener | 이벤트가 발생할 때 호출할 메서드를 포함하는 사용자가 구현한 인터페이스를 사용합니다. |
| useCapture | Boolean | true인 경우 useCapture는 사용자가 캡처를 시작하기를 원함을 나타냅니다. 캡처를 시작한 후 지정된 유형의 모든 이벤트가 registered 로 발송됩니다.[`IEventListener`](../../ieventlistener/) 트리에서 그 아래에 있는 이벤트 대상으로 발송되기 전에. 트리를 통해 위쪽으로 버블링되는 이벤트는[`IEventListener`](../../ieventlistener/) 캡처를 사용하도록 지정되었습니다. |

### 비고

경우[`IEventListener`](../../ieventlistener/) 에 추가됩니다[`EventTarget`](../../../aspose.svg.dom/eventtarget/) 이벤트를 처리하는 동안 현재 작업에 의해 트리거 되지 않지만 버블링 단계와 같은 이벤트 흐름의 이후 단계에서 트리거될 수 있습니다.

동일한 이벤트 리스너가 여러 개 등록된 경우[`EventTarget`](../../../aspose.svg.dom/eventtarget/)동일한 매개변수를 사용하면 중복 인스턴스가 삭제됩니다. [`IEventListener`](../../ieventlistener/) 두 번 호출되고 폐기되기 때문에 the 로 제거할 필요가 없습니다.[`RemoveEventListener`](../removeeventlistener/) 방법.

### 또한보십시오

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* 네임스페이스 [Aspose.Svg.Dom.Events](../../ieventtarget/)
* 집회 [Aspose.SVG](../../../)


