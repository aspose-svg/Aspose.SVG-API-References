---
title: "IEventTarget.AddEventListener"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IEventTarget AddEventListener メソッド。このメソッドはイベントターゲットにイベントリスナーを登録できるようにします。"
type: docs
weight: 10
url: /ja/net/aspose.svg.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(*string, [IEventListener](../../ieventlistener/)*) {#addeventlistener}

このメソッドは、イベントターゲット上でイベントリスナーの登録を可能にします。

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | String | ユーザーが登録するイベントタイプ |
| リスナー | IEventListener | イベントが発生したときに呼び出されるメソッドを含む、ユーザーが実装したインターフェイスを受け取ります。 |

## 備考

もし [`IEventListener`](../../ieventlistener/) がイベントを処理中の [`EventTarget`](../../../aspose.svg.dom/eventtarget/) に追加された場合、現在のアクションではトリガーされませんが、バブリングフェーズなどイベントフローの後の段階でトリガーされる可能性があります。

同じパラメータで同一の Event Listener が同一の [`EventTarget`](../../../aspose.svg.dom/eventtarget/) に複数登録された場合、重複したインスタンスは破棄されます。これにより [`IEventListener`](../../ieventlistener/) が二度呼び出されることはなく、破棄されたため [`RemoveEventListener`](../removeeventlistener/) メソッドで削除する必要もありません。

### 参照

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#addeventlistener_1}

このメソッドは、イベントターゲット上でイベントリスナーの登録を可能にします。

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | String | ユーザーが登録するイベントタイプ |
| リスナー | IEventListener | イベントが発生したときに呼び出されるメソッドを含む、ユーザーが実装したインターフェイスを受け取ります。 |
| useCapture | Boolean | true の場合、useCapture はユーザーがキャプチャを開始したいことを示します。キャプチャが開始されると、指定されたタイプのすべてのイベントは、ツリー内の下位の Event Target にディスパッチされる前に、登録された [`IEventListener`](../../ieventlistener/) にディスパッチされます。ツリー上方向にバブリングするイベントは、キャプチャ用に指定された [`IEventListener`](../../ieventlistener/) をトリガーしません。 |

## 備考

もし [`IEventListener`](../../ieventlistener/) がイベントを処理中の [`EventTarget`](../../../aspose.svg.dom/eventtarget/) に追加された場合、現在のアクションではトリガーされませんが、バブリングフェーズなどイベントフローの後の段階でトリガーされる可能性があります。

同じパラメータで同一の Event Listener が同一の [`EventTarget`](../../../aspose.svg.dom/eventtarget/) に複数登録された場合、重複したインスタンスは破棄されます。これにより [`IEventListener`](../../ieventlistener/) が二度呼び出されることはなく、破棄されたため [`RemoveEventListener`](../removeeventlistener/) メソッドで削除する必要もありません。

### 参照

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
