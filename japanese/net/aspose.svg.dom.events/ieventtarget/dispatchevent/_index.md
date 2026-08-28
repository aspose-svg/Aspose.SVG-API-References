---
title: "IEventTarget.DispatchEvent"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IEventTarget DispatchEvent メソッド。このメソッドは実装のイベントモデルへイベントをディスパッチできるようにします。"
type: docs
weight: 20
url: /ja/net/aspose.svg.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

このメソッドは、実装のイベントモデルへイベントをディスパッチすることを可能にします。

```csharp
public bool DispatchEvent(Event @event)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| イベント | イベント | イベントの処理に使用されるイベントタイプ、動作、およびコンテキスト情報を指定します。 |

### 戻り値

[`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) の戻り値は、イベントを処理したリスナーのいずれかが [`PreventDefault`](../../event/preventdefault/) を呼び出したかどうかを示します。[`PreventDefault`](../../event/preventdefault/) が呼び出された場合は false、そうでない場合は true が返されます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) |  |

## 備考

この方法でディスパッチされたイベントは、実装が直接ディスパッチするイベントと同じキャプチャおよびバブリングの動作を持ちます。イベントのターゲットは、[`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) が呼び出された [`EventTarget`](../../../aspose.svg.dom/eventtarget/) です。

### 参照

* class [Event](../../event/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
