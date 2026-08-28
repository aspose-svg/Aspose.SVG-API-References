---
title: "ErrorEvent クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Events.ErrorEvent クラス。ErrorEvent は実行時に発生したエラーに関するコンテキスト情報を提供します。"
type: docs
weight: 2910
url: /ja/net/aspose.svg.dom.events/errorevent/
---
## ErrorEvent class

`ErrorEvent` は実行時に発生したエラーに関するコンテキスト情報を提供します。

```csharp
public class ErrorEvent : Event
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(*Exception*) | `ErrorEvent` クラスの新しいインスタンスを初期化します。 |
| [ErrorEvent](errorevent/#constructor)(*IDictionary&lt;string, object&gt;*) | `ErrorEvent` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | イベントがバブリングイベントかどうかを示すために使用します。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | イベントのデフォルトアクションを防止できるかどうかを示すために使用します。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [ColNo](../../aspose.svg.dom.events/errorevent/colno/) { get; } | colno 属性は初期化された値を返す必要があります。オブジェクト作成時にこの属性は 0 に初期化されます。これはスクリプト内でエラーが発生した列番号を表します。 |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | 現在処理中の [`IEventListener`](../ieventlistener/) を持つ [`IEventTarget`](../ieventtarget/) を示すために使用します。キャプチャおよびバブリング時に特に有用です。 |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [Error](../../aspose.svg.dom.events/errorevent/error/) { get; } | error 属性は初期化された値を返す必要があります。オブジェクト作成時にこの属性は null に初期化されます。適切な場合は、エラーを表すオブジェクト（例：捕捉されなかった DOM 例外の場合の例外オブジェクト）に設定されます。 |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | 現在評価されているイベントフローのフェーズを示すために使用します。 |
| [FileName](../../aspose.svg.dom.events/errorevent/filename/) { get; } | filename 属性は初期化された値を返す必要があります。オブジェクト作成時にこの属性は空文字列に初期化されます。これはエラーが元々発生したスクリプトの絶対 URL を表します。 |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted 属性は初期化された値を返す必要があります。イベント作成時にこの属性は false に初期化されます。 |
| [LineNo](../../aspose.svg.dom.events/errorevent/lineno/) { get; } | lineno 属性は初期化された値を返す必要があります。オブジェクト作成時にこの属性は 0 に初期化されます。これはスクリプト内でエラーが発生した行番号を表します。 |
| [Message](../../aspose.svg.dom.events/errorevent/message/) { get; } | message 属性は初期化された値を返す必要があります。オブジェクト作成時にこの属性は空文字列に初期化されます。これはエラーメッセージを表します。 |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | イベントが元々ディスパッチされた [`IEventTarget`](../ieventtarget/) を示すために使用します。 |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | イベントが作成された時刻（エポックからのミリ秒）を指定するために使用します。一部のシステムがこの情報を提供しない場合、timeStamp の値はすべてのイベントで利用できないことがあります。利用できない場合は 0 が返されます。エポック時刻の例としてはシステム起動時や 1970年1月1日 0:0:0 UTC があります。 |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | イベントの名前（大文字小文字を区別しません）。名前は XML 名である必要があります。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | [`InitEvent`](../event/initevent/) メソッドは、[`IDocumentEvent`](../idocumentevent/) インターフェイスを介して作成された [`Event`](../event/) の値を初期化するために使用されます。 |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、[`PreventDefault`](../event/preventdefault/) メソッドはイベントがキャンセルされることを示すために使用され、実装が通常行うデフォルトアクションが実行されなくなります。 |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、現在のリスナーの後に登録されたイベントリスナーにイベントが到達するのを防ぎ、ツリー内でディスパッチされた場合は他のオブジェクトへの到達も防止します。 |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | [`StopPropagation`](../event/stoppropagation/) メソッドは、イベントフロー中のイベントのさらなる伝播を防止するために使用されます。 |

### 参照

* class [Event](../event/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
