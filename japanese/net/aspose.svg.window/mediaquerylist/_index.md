---
title: "MediaQueryList クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Window.MediaQueryList クラス。MediaQueryList オブジェクトは、ドキュメントに適用されたメディアクエリに関する情報を保持し、ドキュメントの状態に対する即時およびイベント駆動のマッチングの両方をサポートします。CSSOM View Module 仕様をご覧ください https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /ja/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

MediaQueryList オブジェクトは、ドキュメントに適用されたメディアクエリに関する情報を保持し、ドキュメントの状態に対する即時およびイベント駆動のマッチングをサポートします。CSSOM View Module 仕様をご覧ください: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | Context オブジェクトに関連付けられたドキュメント。 |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | ドキュメントが現在メディアクエリリストと一致している場合は true、そうでない場合は false を返すブール値。 |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | シリアライズされたメディアクエリを表す文字列。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | MediaQueryList のマッチ状態変更イベントリスナーを追加します。 |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | 指定された[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)にイベントをディスパッチし、（同期的に）影響を受けたEventListenersを適切な順序で呼び出します。通常のイベント処理規則（キャプチャフェーズおよびオプションのバブリングフェーズを含む）も、[`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)で手動でディスパッチされたイベントに適用されます。 |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)がイベントを処理中に[`EventTarget`](../../aspose.svg.dom/eventtarget/)から削除された場合、現在のアクションによってトリガーされることはありません。イベントリスナーは削除された後は決して呼び出されません。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)がイベントを処理中に[`EventTarget`](../../aspose.svg.dom/eventtarget/)から削除された場合、現在のアクションによってトリガーされることはありません。イベントリスナーは削除された後は決して呼び出されません。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)がイベントを処理中に[`EventTarget`](../../aspose.svg.dom/eventtarget/)から削除された場合、現在のアクションによってトリガーされることはありません。イベントリスナーは削除された後は決して呼び出されません。 |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | MediaQueryList の matches 状態変化イベントリスナーを削除します。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | matches 状態が変化したときに MediaQueryList で発火するイベントです。 |

### 参照

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
