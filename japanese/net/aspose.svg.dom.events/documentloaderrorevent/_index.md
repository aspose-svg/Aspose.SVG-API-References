---
title: Class DocumentLoadErrorEvent
second_title: Aspose.SVG for .NET API リファレンス
description: Aspose.Svg.Dom.Events.DocumentLoadErrorEvent クラス. DocumentLoadErrorEvent要求されたリソースが利用できない場合に発生します.
type: docs
weight: 900
url: /ja/net/aspose.svg.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

`DocumentLoadErrorEvent`要求されたリソースが利用できない場合に発生します.

```csharp
public class DocumentLoadErrorEvent : ErrorEvent
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | イベントがバブリング イベントかどうかを示すために使用されます。イベントがバブルできる場合、値は true、それ以外の場合、値は false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | イベントのデフォルト アクションを防止できるかどうかを示すために使用されます。デフォルト アクションを防止できる場合、値は true であり、それ以外の場合、値は false. です。 |
| [ColNo](../../aspose.svg.dom.events/errorevent/colno/) { get; } | colno 属性は、初期化された値を返す必要があります。オブジェクトの作成時に、この属性をゼロに初期化する必要があります。スクリプト内でエラーが発生した列番号を表します。 |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | を示すために使用されます[`IEventTarget`](../ieventtarget/)だれの[`IEventListener`](../ieventlistener/) は現在処理中です. これは、キャプチャとバブリング中に特に役立ちます. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | cancelable 属性値が true のときに preventDefault() が呼び出された場合は true を返し、それ以外の場合は false を返します。 |
| [Error](../../aspose.svg.dom.events/errorevent/error/) { get; } | error 属性は、初期化された値を返す必要があります。オブジェクトの作成時に、この属性を null に初期化する必要があります。必要に応じて、エラーを表すオブジェクトに設定されます (例: キャッチされていない DOM 例外の場合の例外オブジェクト). |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | イベントフローのどのフェーズが現在評価されているかを示すために使用されます. |
| [FileName](../../aspose.svg.dom.events/errorevent/filename/) { get; } | filename 属性は、初期化された値を返す必要があります。オブジェクトの作成時に、この属性を空の文字列に初期化する必要があります。エラーが最初に発生したスクリプトの絶対 URL を表します。 |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted 属性は、初期化された値を返す必要があります。イベントが作成されたら、属性を false. に初期化する必要があります。 |
| [LineNo](../../aspose.svg.dom.events/errorevent/lineno/) { get; } | lineno 属性は、初期化された値を返す必要があります。オブジェクトの作成時に、この属性をゼロに初期化する必要があります。スクリプトでエラーが発生した行番号を表します. |
| [Message](../../aspose.svg.dom.events/errorevent/message/) { get; } | メッセージ属性は、初期化された値を返す必要があります。オブジェクトの作成時に、この属性を空の文字列に初期化する必要があります。エラーメッセージを表します. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | を示すために使用されます[`IEventTarget`](../ieventtarget/)イベントが最初にディスパッチされた先. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | イベントが作成された時刻 (エポックからのミリ秒単位) を指定するために使用されます。 、値 0 が返されます。 エポック時間の例は、システムの開始時間または 1970 年 1 月 1 日の 0:0:0 UTC です。 |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | イベントの名前 (大文字と小文字を区別しない)。名前は XML 名でなければなりません. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | [`InitEvent`](../event/initevent/)メソッドは、の値を初期化するために使用されます[`Event`](../event/) the で作成[`IDocumentEvent`](../idocumentevent/)インターフェイス. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、[`PreventDefault`](../event/preventdefault/)メソッドは、イベントがキャンセルされることを示すために使用されます。 は、イベントの結果として実装によって通常実行されるデフォルト アクションが発生しないことを意味します。 |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、イベントが現在のイベントリスナーの後に登録されたイベントリスナーに到達するのを防ぎ、ツリーでディスパッチされたときに、イベントが他のオブジェクトに到達するのを防ぎます. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | [`StopPropagation`](../event/stoppropagation/)メソッドが使用され、イベント フロー中にイベントがさらに伝播するのを防ぎます。 |

### 関連項目

* class [ErrorEvent](../errorevent/)
* 名前空間 [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* 組み立て [Aspose.SVG](../../)


