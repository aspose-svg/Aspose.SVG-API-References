---
title: "WheelEvent クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Events.WheelEvent クラス。WheelEvent インターフェイスは、ホイールイベントに関連する特定のコンテキスト情報を提供します。WheelEvent インターフェイスのインスタンスを作成するには、オプションの WheelEventInit 辞書を渡して WheelEvent コンストラクタを使用します。"
type: docs
weight: 3010
url: /ja/net/aspose.svg.dom.events/wheelevent/
---
## WheelEvent class

WheelEvent インターフェイスは、ホイールイベントに関連する特定のコンテキスト情報を提供します。WheelEvent インターフェイスのインスタンスを作成するには、WheelEvent コンストラクタを使用し、オプションの WheelEventInit 辞書を渡します。

```csharp
public class WheelEvent : MouseEvent
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(*string*) | `WheelEvent` クラスの新しいインスタンスを初期化します。 |
| [WheelEvent](wheelevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | `WheelEvent` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/mouseevent/altkey/) { get; } | altKey 属性を参照してください。 |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | イベントがバブリングイベントかどうかを示すために使用します。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [Button](../../aspose.svg.dom.events/mouseevent/button/) { get; } | マウスボタンの押下または解放によって発生するマウスイベントでは、どのポインターデバイスのボタンが状態変化したかを示すために button を使用しなければなりません。 |
| [Buttons](../../aspose.svg.dom.events/mouseevent/buttons/) { get; } | すべてのマウスイベントにおいて、現在押されているマウスボタンの組み合わせをビットマスクで表すために buttons を使用しなければなりません。 |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | イベントのデフォルトアクションを防止できるかどうかを示すために使用します。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [ClientX](../../aspose.svg.dom.events/mouseevent/clientx/) { get; } | イベントが発生した水平座標（イベントに関連付けられたビューポートに対する相対座標）。 |
| [ClientY](../../aspose.svg.dom.events/mouseevent/clienty/) { get; } | イベントが発生した垂直座標（イベントに関連付けられたビューポートに対する相対座標）。 |
| [CtrlKey](../../aspose.svg.dom.events/mouseevent/ctrlkey/) { get; } | ctrlKey 属性を参照してください。 |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | 現在処理中の [`IEventListener`](../ieventlistener/) を持つ [`IEventTarget`](../ieventtarget/) を示すために使用します。キャプチャおよびバブリング時に特に有用です。 |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [DeltaMode](../../aspose.svg.dom.events/wheelevent/deltamode/) { get; } | deltaMode 属性は、デルタ値の測定単位を示します。デフォルト値は DOM_DELTA_PIXEL（ピクセル）です。 |
| [DeltaX](../../aspose.svg.dom.events/wheelevent/deltax/) { get; } | ホイールイベントのデフォルト動作がスクロールであるユーザーエージェントでは、イベントがキャンセルされない場合にスクロールされる x 軸方向の測定値（ピクセル、行、またはページ単位）でなければなりません。そうでない場合、これは x 軸周りのホイールデバイスの動きを示す実装固有の測定値（ピクセル、行、またはページ単位）です。 |
| [DeltaY](../../aspose.svg.dom.events/wheelevent/deltay/) { get; } | ホイールイベントのデフォルト動作がスクロールであるユーザーエージェントでは、イベントがキャンセルされない場合にスクロールされる y 軸方向の測定値（ピクセル、行、またはページ単位）でなければなりません。そうでない場合、これは y 軸周りのホイールデバイスの動きを示す実装固有の測定値（ピクセル、行、またはページ単位）です。 |
| [DeltaZ](../../aspose.svg.dom.events/wheelevent/deltaz/) { get; } | ホイールイベントのデフォルト動作がスクロールであるユーザーエージェントでは、イベントがキャンセルされない場合にスクロールされる z 軸方向の測定値（ピクセル、行、またはページ単位）でなければなりません。そうでない場合、これは z 軸周りのホイールデバイスの動きを示す実装固有の測定値（ピクセル、行、またはページ単位）です。 |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | イベントのタイプに応じて、Event に関する詳細情報を指定します。 |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | 現在評価されているイベントフローのフェーズを示すために使用します。 |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted 属性は初期化された値を返す必要があります。イベント作成時にこの属性は false に初期化されます。 |
| [MetaKey](../../aspose.svg.dom.events/mouseevent/metakey/) { get; } | metaKey 属性を参照してください。 |
| [RelatedTarget](../../aspose.svg.dom.events/mouseevent/relatedtarget/) { get; } | イベントの種類に応じて、UI イベントに関連する二次的な EventTarget を識別するために使用されます。 |
| [ScreenX](../../aspose.svg.dom.events/mouseevent/screenx/) { get; } | イベントが発生した水平座標（画面座標系の原点からの相対位置）です。 |
| [ScreenY](../../aspose.svg.dom.events/mouseevent/screeny/) { get; } | イベントが発生した垂直座標（画面座標系の原点からの相対位置）です。 |
| [ShiftKey](../../aspose.svg.dom.events/mouseevent/shiftkey/) { get; } | shiftKey 属性を参照してください。 |
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

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DOM_DELTA_LINE](../../aspose.svg.dom.events/wheelevent/dom_delta_line/) | デルタの測定単位は個々のテキスト行でなければなりません。これは多くのフォームコントロールで当てはまります。 |
| const [DOM_DELTA_PAGE](../../aspose.svg.dom.events/wheelevent/dom_delta_page/) | デルタの測定単位はページでなければなりません。単一の画面として定義するか、区切られたページとして定義します。 |
| const [DOM_DELTA_PIXEL](../../aspose.svg.dom.events/wheelevent/dom_delta_pixel/) | デルタの測定単位はピクセルでなければなりません。これはほとんどのオペレーティングシステムおよび実装構成で最も一般的なケースです。 |

### 参照

* class [MouseEvent](../mouseevent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
