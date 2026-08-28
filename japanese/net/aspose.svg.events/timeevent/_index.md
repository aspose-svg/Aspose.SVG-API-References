---
title: "TimeEvent クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Events.TimeEvent クラス。TimeEvent インターフェイスは、Time イベントに関連する特定のコンテキスト情報を提供します。発生し得るイベントの種類は beginEvent、endEvent、repeatEvent です。"
type: docs
weight: 3720
url: /ja/net/aspose.svg.events/timeevent/
---
## TimeEvent class

TimeEvent インターフェイスは、時間イベントに関連する特定のコンテキスト情報を提供します。発生し得るイベントの種類は、beginEvent、endEvent、repeatEvent です。

```csharp
public class TimeEvent : Event
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | イベントがバブリングイベントかどうかを示すために使用します。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | イベントのデフォルトアクションを防止できるかどうかを示すために使用します。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | 現在処理中の [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) を持つ [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) を示すために使用されます。キャプチャおよびバブリング時に特に有用です。 |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [Detail](../../aspose.svg.events/timeevent/detail/) { get; } | イベントのタイプに応じて、Event に関する詳細情報を指定します。このイベントタイプでは、アニメーションの繰り返し回数を示します。 |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | 現在評価されているイベントフローのフェーズを示すために使用します。 |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted 属性は初期化された値を返す必要があります。イベント作成時にこの属性は false に初期化されます。 |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | イベントが元々ディスパッチされた ``[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)`` を示すために使用されます。 |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | イベントが作成された時刻（エポックからのミリ秒）を指定するために使用します。一部のシステムがこの情報を提供しない場合、timeStamp の値はすべてのイベントで利用できないことがあります。利用できない場合は 0 が返されます。エポック時刻の例としてはシステム起動時や 1970年1月1日 0:0:0 UTC があります。 |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | イベントの名前（大文字小文字を区別しません）。名前は XML 名である必要があります。 |
| [View](../../aspose.svg.events/timeevent/view/) { get; } | view 属性は、イベントが生成された AbstractView [DOM2VIEWS] を識別します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | ``[`InitEvent`](../../aspose.svg.dom.events/event/initevent/)`` メソッドは、``[`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/)`` インターフェイスを介して作成された ``[`Event`](../../aspose.svg.dom.events/event/)`` の値を初期化するために使用されます。 |
| [InitTimeEvent](../../aspose.svg.events/timeevent/inittimeevent/)(*string, [IAbstractView](../../aspose.svg.dom.views/iabstractview/), long*) | initTimeEvent メソッドは、DocumentEvent インターフェイスを介して作成された TimeEvent の値を初期化するために使用されます。このメソッドは、TimeEvent が dispatchEvent メソッドによってディスパッチされる前にのみ呼び出すことができ、必要に応じてそのフェーズ中に複数回呼び出すことができます。複数回呼び出された場合、最後の呼び出しが優先されます。 |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、``[`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/)`` メソッドは、イベントがキャンセルされることを示すために使用されます。これにより、実装が通常イベントの結果として行うデフォルトの動作は実行されません。 |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、現在のリスナーの後に登録されたイベントリスナーにイベントが到達するのを防ぎ、ツリー内でディスパッチされた場合は他のオブジェクトへの到達も防止します。 |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | ``[`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/)`` メソッドは、イベントフロー中にイベントのさらなる伝播を防止するために使用されます。 |

### 参照

* class [Event](../../aspose.svg.dom.events/event/)
* namespace [Aspose.Svg.Events](../../aspose.svg.events/)
* assembly [Aspose.SVG](../../)
