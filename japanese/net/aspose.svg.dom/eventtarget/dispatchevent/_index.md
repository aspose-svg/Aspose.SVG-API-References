---
title: "EventTarget.DispatchEvent"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "EventTarget DispatchEvent メソッド。指定された IEventTarget に対してイベントを同期的にディスパッチし、影響を受けた EventListeners を適切な順序で呼び出します。キャプチャフェーズやオプションのバブリングフェーズを含む通常のイベント処理規則は、DispatchEvent で手動でディスパッチされたイベントにも適用されます。"
type: docs
weight: 30
url: /ja/net/aspose.svg.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

指定された [`IEventTarget`](../../../aspose.svg.dom.events/ieventtarget/) にイベントをディスパッチし、（同期的に）影響を受けた EventListeners を適切な順序で呼び出します。通常のイベント処理規則（キャプチャとオプションのバブリングフェーズを含む）は、[`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/) で手動でディスパッチされたイベントにも適用されます。

```csharp
public bool DispatchEvent(Event @event)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| イベント | イベント | イベントの処理に使用されるイベントタイプ、動作、およびコンテキスト情報を指定します。 |

### 戻り値

`DispatchEvent` の戻り値は、イベントを処理したリスナーのいずれかが [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/) を呼び出したかどうかを示します。[`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/) が呼び出された場合は false、そうでない場合は true です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../domexception/) |  |

## 備考

この方法でディスパッチされたイベントは、実装によって直接ディスパッチされたイベントと同じキャプチャおよびバブリングの動作を持ちます。イベントのターゲットは `DispatchEvent` が呼び出された [`EventTarget`](../) です。

### 参照

* class [Event](../../../aspose.svg.dom.events/event/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
