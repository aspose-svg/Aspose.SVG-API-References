---
title: "IEventTarget.RemoveEventListener"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IEventTarget RemoveEventListener メソッド。このメソッドはイベントターゲットからイベントリスナーを削除できます。イベント処理中に IEventListener が EventTarget から削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません"
type: docs
weight: 30
url: /ja/net/aspose.svg.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [IEventListener](../../ieventlistener/)*) {#removeeventlistener}

このメソッドはイベントターゲットからイベントリスナーを削除できます。[`IEventListener`](../../ieventlistener/) が [`EventTarget`](../../../aspose.svg.dom/eventtarget/) から、イベント処理中に削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | String | 削除される [`IEventListener`](../../ieventlistener/) のイベントタイプを指定します。 |
| listener | IEventListener | パラメータ [`IEventListener`](../../ieventlistener/) は削除される [`IEventListener`](../../ieventlistener/) を示します。 |

### 参照

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#removeeventlistener_1}

このメソッドはイベントターゲットからイベントリスナーを削除できます。[`IEventListener`](../../ieventlistener/) が [`EventTarget`](../../../aspose.svg.dom/eventtarget/) から、イベント処理中に削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | String | 削除される [`IEventListener`](../../ieventlistener/) のイベントタイプを指定します。 |
| listener | IEventListener | パラメータ [`IEventListener`](../../ieventlistener/) は削除される [`IEventListener`](../../ieventlistener/) を示します。 |
| useCapture | Boolean | 削除される EventListener がキャプチャリスナーとして登録されているかどうかを指定します。リスナーが 2 回登録されている場合、1 つはキャプチャあり、もう 1 つはキャプチャなしで、各々を個別に削除する必要があります。キャプチャリスナーの削除は、同じリスナーの非キャプチャバージョンには影響せず、その逆も同様です。 |

### 参照

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
