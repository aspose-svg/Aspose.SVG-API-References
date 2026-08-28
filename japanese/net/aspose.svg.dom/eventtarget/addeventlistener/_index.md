---
title: "EventTarget.AddEventListener"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "EventTarget AddEventListener メソッド。指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。"
type: docs
weight: 20
url: /ja/net/aspose.svg.dom/eventtarget/addeventlistener/
---
## AddEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#addeventlistener}

指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。

これは、呼び出された [`EventTarget`](../) の指定されたイベントタイプのイベントリスナーリストに、関数または [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) を実装したオブジェクトを追加することで機能します。関数またはオブジェクトがすでにこのターゲットのイベントリスナーリストに存在する場合、二度目は追加されません。

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | String | ユーザーが登録するイベントタイプ |
| handler | DOMEventHandler | イベントが発生したときに呼び出される [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) を受け取ります。 |
| useCapture | Boolean | true の場合、useCapture はユーザーがキャプチャを開始したいことを示します。キャプチャを開始すると、指定されたタイプのすべてのイベントは、ツリー内の下位の Event Target にディスパッチされる前に、登録された [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) にディスパッチされます。ツリー上方向にバブリングするイベントは、キャプチャ用に指定された [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) をトリガーしません。 |

## 備考

イベントが処理中に [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) が [`EventTarget`](../) に追加された場合、現在のアクションではトリガーされませんが、バブリングフェーズなどイベントフローの後の段階でトリガーされる可能性があります。

同じパラメータで同一の Event Listener が同一の [`EventTarget`](../) に複数登録された場合、重複したインスタンスは破棄されます。これにより [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) が二度呼び出されることはなく、破棄されたため [`RemoveEventListener`](../removeeventlistener/) メソッドで削除する必要もありません。

### 参照

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#addeventlistener_1}

指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。

これは、呼び出された [`EventTarget`](../) の指定されたイベントタイプのイベントリスナーリストに、関数または [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) を実装したオブジェクトを追加することで機能します。関数またはオブジェクトがすでにこのターゲットのイベントリスナーリストに存在する場合、二度目は追加されません。

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | String | ユーザーが登録するイベントタイプ |
| リスナー | IEventListener | イベントが発生したときに呼び出されるメソッドを含む、ユーザーが実装したインターフェイスを受け取ります。 |

## 備考

イベントが処理中に [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) が [`EventTarget`](../) に追加された場合、現在のアクションではトリガーされませんが、バブリングフェーズなどイベントフローの後の段階でトリガーされる可能性があります。

同じパラメータで同一の Event Listener が同一の [`EventTarget`](../) に複数登録された場合、重複したインスタンスは破棄されます。これにより [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) が二度呼び出されることはなく、破棄されたため [`RemoveEventListener`](../removeeventlistener/) メソッドで削除する必要もありません。

### 参照

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#addeventlistener_2}

指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。

これは、呼び出された [`EventTarget`](../) の指定されたイベントタイプのイベントリスナーリストに、関数または [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) を実装したオブジェクトを追加することで機能します。関数またはオブジェクトがすでにこのターゲットのイベントリスナーリストに存在する場合、二度目は追加されません。

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | String | ユーザーが登録するイベントタイプ |
| リスナー | IEventListener | イベントが発生したときに呼び出されるメソッドを含む、ユーザーが実装したインターフェイスを受け取ります。 |
| useCapture | Boolean | true の場合、useCapture はユーザーがキャプチャを開始したいことを示します。キャプチャを開始すると、指定されたタイプのすべてのイベントは、ツリー内の下位の Event Target にディスパッチされる前に、登録された [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) にディスパッチされます。ツリー上方向にバブリングするイベントは、キャプチャ用に指定された [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) をトリガーしません。 |

## 備考

イベントが処理中に [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) が [`EventTarget`](../) に追加された場合、現在のアクションではトリガーされませんが、バブリングフェーズなどイベントフローの後の段階でトリガーされる可能性があります。

同じパラメータで同一の Event Listener が同一の [`EventTarget`](../) に複数登録された場合、重複したインスタンスは破棄されます。これにより [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) が二度呼び出されることはなく、破棄されたため [`RemoveEventListener`](../removeeventlistener/) メソッドで削除する必要もありません。

### 参照

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
