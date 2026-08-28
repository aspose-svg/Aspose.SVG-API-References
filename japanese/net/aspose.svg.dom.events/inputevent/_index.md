---
title: "InputEvent クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Events.InputEvent クラス。DOM が更新されるたびに、入力イベントは通知として送信されます。"
type: docs
weight: 2970
url: /ja/net/aspose.svg.dom.events/inputevent/
---
## InputEvent class

DOM が更新されるたびに、入力イベントが通知として送信されます。

```csharp
public class InputEvent : UIEvent
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [InputEvent](inputevent/#constructor)(*string*) | `InputEvent` クラスの新しいインスタンスを初期化します。 |
| [InputEvent](inputevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | `InputEvent` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | イベントがバブリングイベントかどうかを示すために使用します。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | イベントのデフォルトアクションを防止できるかどうかを示すために使用します。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | 現在処理中の [`IEventListener`](../ieventlistener/) を持つ [`IEventTarget`](../ieventtarget/) を示すために使用します。キャプチャおよびバブリング時に特に有用です。 |
| [Data](../../aspose.svg.dom.events/inputevent/data/) { get; } | data は、入力方式によって生成された文字の値を保持します。これは単一の Unicode 文字または空でない Unicode 文字列 [Unicode] である可能性があります。文字は、[UAX15] で定義された Unicode 正規化形式 NFC に従って正規化されるべきです。この属性は空文字列を含むことがあります。 |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | イベントのタイプに応じて、Event に関する詳細情報を指定します。 |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | 現在評価されているイベントフローのフェーズを示すために使用します。 |
| [IsComposing](../../aspose.svg.dom.events/inputevent/iscomposing/) { get; } | 入力イベントが合成セッションの一部として発生した場合は true です。すなわち、compositionstart イベントの後で対応する compositionend イベントの前です。この属性の初期化されていない値は false でなければなりません。 |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted 属性は初期化された値を返す必要があります。イベント作成時にこの属性は false に初期化されます。 |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | イベントが元々ディスパッチされた [`IEventTarget`](../ieventtarget/) を示すために使用します。 |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | イベントが作成された時刻（エポックからのミリ秒）を指定するために使用します。一部のシステムがこの情報を提供しない場合、timeStamp の値はすべてのイベントで利用できないことがあります。利用できない場合は 0 が返されます。エポック時刻の例としてはシステム起動時や 1970年1月1日 0:0:0 UTC があります。 |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | イベントの名前（大文字小文字を区別しません）。名前は XML 名である必要があります。 |
| [View](../../aspose.svg.dom.events/uievent/view/) { get; } | view 属性は、イベントが生成されたウィンドウを識別します。属性の未初期化値は null である必要があります。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | [`InitEvent`](../event/initevent/) メソッドは、[`IDocumentEvent`](../idocumentevent/) インターフェイスを介して作成された [`Event`](../event/) の値を初期化するために使用されます。 |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、[`PreventDefault`](../event/preventdefault/) メソッドはイベントがキャンセルされることを示すために使用され、実装が通常行うデフォルトアクションが実行されなくなります。 |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、現在のリスナーの後に登録されたイベントリスナーにイベントが到達するのを防ぎ、ツリー内でディスパッチされた場合は他のオブジェクトへの到達も防止します。 |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | [`StopPropagation`](../event/stoppropagation/) メソッドは、イベントフロー中のイベントのさらなる伝播を防止するために使用されます。 |

### 参照

* class [UIEvent](../uievent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
