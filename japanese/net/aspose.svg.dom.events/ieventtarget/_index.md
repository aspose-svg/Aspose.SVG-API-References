---
title: "IEventTarget インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Events.IEventTarget インターフェイス。EventTarget インターフェイスは、DOM イベントモデルをサポートする実装のすべての Node に実装されています。そのため、このインターフェイスは Node インターフェイスのインスタンスに対してバインディング固有のキャストメソッドを使用して取得できます。このインターフェイスは、EventTarget 上でイベントリスナーの登録と削除、およびイベントをその IEventTarget にディスパッチすることを可能にします。"
type: docs
weight: 2960
url: /ja/net/aspose.svg.dom.events/ieventtarget/
---
## IEventTarget interface

[`EventTarget`](../../aspose.svg.dom/eventtarget/) インターフェイスは、DOM イベントモデルをサポートする実装のすべての Node に実装されています。そのため、このインターフェイスは Node インターフェイスのインスタンスに対してバインディング固有のキャストメソッドを使用して取得できます。このインターフェイスは、[`EventTarget`](../../aspose.svg.dom/eventtarget/) 上でイベントリスナーの登録と削除、およびそれらのイベントを `IEventTarget` にディスパッチすることを可能にします。

```csharp
public interface IEventTarget
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener)(*string, [IEventListener](../ieventlistener/)*) | このメソッドは、イベントターゲット上でイベントリスナーの登録を可能にします。 |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | このメソッドは、イベントターゲット上でイベントリスナーの登録を可能にします。 |
| [DispatchEvent](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)(*[Event](../event/)*) | このメソッドは、実装のイベントモデルへイベントをディスパッチすることを可能にします。 |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(*string, [IEventListener](../ieventlistener/)*) | このメソッドは、イベントターゲットからイベントリスナーの削除を可能にします。[`IEventListener`](../ieventlistener/) がイベント処理中に [`EventTarget`](../../aspose.svg.dom/eventtarget/) から削除された場合、現在のアクションによってトリガーされることはありません。イベントリスナーは削除された後は決して呼び出されません。 |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | このメソッドは、イベントターゲットからイベントリスナーの削除を可能にします。[`IEventListener`](../ieventlistener/) がイベント処理中に [`EventTarget`](../../aspose.svg.dom/eventtarget/) から削除された場合、現在のアクションによってトリガーされることはありません。イベントリスナーは削除された後は決して呼び出されません。 |

### 参照

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
