---
title: "EventTarget.RemoveEventListener"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "EventTarget RemoveEventListener メソッド。このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。イベントが処理中に IEventListener が EventTarget から削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。"
type: docs
weight: 50
url: /ja/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#removeeventlistener}

このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。イベントが処理中に [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) が [`EventTarget`](../) から削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | String | 削除される [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) のイベントタイプを指定します。 |
| handler | DOMEventHandler | [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) パラメータは削除される [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) を示します。 |
| useCapture | Boolean | 削除される EventListener がキャプチャリスナーとして登録されているかどうかを指定します。リスナーが 2 回登録されている場合、1 つはキャプチャあり、もう 1 つはキャプチャなしで、各々を個別に削除する必要があります。キャプチャリスナーの削除は、同じリスナーの非キャプチャバージョンには影響せず、その逆も同様です。 |

### 参照

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#removeeventlistener_1}

このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。イベントが処理中に [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) が [`EventTarget`](../) から削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | String | 削除される [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) のイベントタイプを指定します。 |
| listener | IEventListener | この [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) パラメータは、削除される [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) を示します。 |

### 参照

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#removeeventlistener_2}

このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。イベントが処理中に [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) が [`EventTarget`](../) から削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | String | 削除される [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) のイベントタイプを指定します。 |
| listener | IEventListener | この [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) パラメータは、削除される [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) を示します。 |
| useCapture | Boolean | 削除される EventListener がキャプチャリスナーとして登録されているかどうかを指定します。リスナーが 2 回登録されている場合、1 つはキャプチャあり、もう 1 つはキャプチャなしで、各々を個別に削除する必要があります。キャプチャリスナーの削除は、同じリスナーの非キャプチャバージョンには影響せず、その逆も同様です。 |

### 参照

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
