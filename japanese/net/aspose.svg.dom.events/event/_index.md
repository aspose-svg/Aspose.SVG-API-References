---
title: "Event クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Events.Event クラス。Event は、イベントを処理するハンドラに対してイベントに関するコンテキスト情報を提供するために使用されます。"
type: docs
weight: 2920
url: /ja/net/aspose.svg.dom.events/event/
---
## Event class

`Event` は、イベントを処理するハンドラに対してイベントに関するコンテキスト情報を提供するために使用されます。

```csharp
public class Event : DOMObject
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Event](event/#constructor)(*string*) | `Event` クラスの新しいインスタンスを初期化します。 |
| [Event](event/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | `Event` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | イベントがバブリングイベントかどうかを示すために使用します。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | イベントのデフォルトアクションを防止できるかどうかを示すために使用します。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | 現在処理中の [`IEventListener`](../ieventlistener/) を持つ [`IEventTarget`](../ieventtarget/) を示すために使用します。キャプチャおよびバブリング時に特に有用です。 |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | 現在評価されているイベントフローのフェーズを示すために使用します。 |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted 属性は初期化された値を返す必要があります。イベント作成時にこの属性は false に初期化されます。 |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | イベントが元々ディスパッチされた [`IEventTarget`](../ieventtarget/) を示すために使用します。 |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | イベントが作成された時刻（エポックからのミリ秒）を指定するために使用します。一部のシステムがこの情報を提供しない場合、timeStamp の値はすべてのイベントで利用できないことがあります。利用できない場合は 0 が返されます。エポック時刻の例としてはシステム起動時や 1970年1月1日 0:0:0 UTC があります。 |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | イベントの名前（大文字小文字を区別しません）。名前は XML 名である必要があります。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | [`InitEvent`](./initevent/) メソッドは、[`IDocumentEvent`](../idocumentevent/) インターフェイスを通じて作成された `Event` の値を初期化するために使用されます。 |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、[`PreventDefault`](./preventdefault/) メソッドは、イベントがキャンセルされることを示すために使用され、実装が通常イベントの結果として行うデフォルトの動作は実行されません。 |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、現在のリスナーの後に登録されたイベントリスナーにイベントが到達するのを防ぎ、ツリー内でディスパッチされた場合は他のオブジェクトへの到達も防止します。 |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | イベントフロー中にイベントのさらなる伝播を防止するために、[`StopPropagation`](./stoppropagation/) メソッドが使用されます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [AtTargetPhase](../../aspose.svg.dom.events/event/attargetphase/) | 現在のイベントフェーズはキャプチャフェーズです。 |
| const [BubblingPhase](../../aspose.svg.dom.events/event/bubblingphase/) | 現在のイベントフェーズはバブリングフェーズです。 |
| const [CapturingPhase](../../aspose.svg.dom.events/event/capturingphase/) | イベントは現在、ターゲット [`IEventTarget`](../ieventtarget/) で評価されています。 |
| const [NonePhase](../../aspose.svg.dom.events/event/nonephase/) | 現在ディスパッチされていないイベントはこのフェーズにあります。 |

## 備考

`Event` を実装するオブジェクトは、通常、イベントハンドラへの最初のパラメータとして渡されます。より具体的なコンテキスト情報は、`Event` から派生した追加インターフェイスを通じてイベントハンドラに渡され、これらのインターフェイスはイベントの種類に直接関連する情報を含みます。これらの派生インターフェイスも、イベントリスナーに渡されるオブジェクトによって実装されます。

### 参照

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
