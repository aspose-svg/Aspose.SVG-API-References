---
title: "KeyboardEvent クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Events.KeyboardEvent クラス。KeyboardEvent インターフェイスは、キーボード デバイスに関連する特定のコンテキスト情報を提供します。各キーボード イベントは、値を使用してキーを参照します。キーボード イベントは、通常、フォーカスがある要素に対して送信されます。"
type: docs
weight: 2980
url: /ja/net/aspose.svg.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent インターフェイスは、キーボードデバイスに関連する特定のコンテキスト情報を提供します。各キーボードイベントは、値を使用してキーを参照します。キーボードイベントは通常、フォーカスを持つ要素に向けられます。

```csharp
public class KeyboardEvent : UIEvent
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(*string*) | `KeyboardEvent` クラスの新しいインスタンスを初期化します。 |
| [KeyboardEvent](keyboardevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | `KeyboardEvent` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/keyboardevent/altkey/) { get; } | Alt（代替）キー（または \"Option\"）修飾子がアクティブな場合は true。属性の未初期化値は false である必要があります。 |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | イベントがバブリングイベントかどうかを示すために使用します。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | イベントのデフォルトアクションを防止できるかどうかを示すために使用します。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [Code](../../aspose.svg.dom.events/keyboardevent/code/) { get; } | code は、押された物理キーを識別する文字列を保持します。現在のキーボードレイアウトや修飾子の状態の影響を受けないため、特定のキーは常に同じ値を返します。 |
| [CtrlKey](../../aspose.svg.dom.events/keyboardevent/ctrlkey/) { get; } | Control（制御）キー修飾子がアクティブな場合は true。属性の未初期化値は false である必要があります。 |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | 現在処理中の [`IEventListener`](../ieventlistener/) を持つ [`IEventTarget`](../ieventtarget/) を示すために使用します。キャプチャおよびバブリング時に特に有用です。 |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | イベントのタイプに応じて、Event に関する詳細情報を指定します。 |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | 現在評価されているイベントフローのフェーズを示すために使用します。 |
| [IsComposing](../../aspose.svg.dom.events/keyboardevent/iscomposing/) { get; } | キーイベントが合成セッションの一部として発生した場合は true（つまり、compositionstart イベントの後、対応する compositionend イベントの前）。属性の未初期化値は false である必要があります。 |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted 属性は初期化された値を返す必要があります。イベント作成時にこの属性は false に初期化されます。 |
| [Key](../../aspose.svg.dom.events/keyboardevent/key/) { get; } | キーは、押されたキーのキー値を保持します。値に印字可能な表現がある場合は、空でない Unicode 文字列でなければならず、本仕様で定義されたキー値を決定するアルゴリズムに従う必要があります。印字可能な表現を持たない制御キーの場合は、キー値決定アルゴリズムに基づいて定義されたキー値セットのいずれかでなければなりません。キーを特定できない実装は、キー値として Unidentified を使用しなければなりません。 |
| [Location](../../aspose.svg.dom.events/keyboardevent/location/) { get; } | location 属性は、デバイス上のキーの論理的な位置を示す情報を含みます。 |
| [MetaKey](../../aspose.svg.dom.events/keyboardevent/metakey/) { get; } | meta（Meta）キー修飾子がアクティブな場合は true。 |
| [Repeat](../../aspose.svg.dom.events/keyboardevent/repeat/) { get; } | キーが長時間押し続けられた場合は true。キーを押し続けると、システム設定で決定されたレートで、keydown、beforeinput、input のイベントがこの順序で繰り返し発生しなければなりません。長押し動作を持つモバイルデバイスでは、repeat 属性が true の最初のキーイベントが長押しの指標として機能しなければなりません。繰り返しが開始されるまでにキーを押し続ける必要がある時間は、設定に依存します。 |
| [ShiftKey](../../aspose.svg.dom.events/keyboardevent/shiftkey/) { get; } | shift（Shift）キー修飾子がアクティブな場合は true。 |
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
| const [DOM_KEY_LOCATION_LEFT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_left/) | キーのアクティベーションは左側のキー位置から発生しました（このキーに複数の可能な位置がある場合）。 |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_numpad/) | キーのアクティベーションはテンキー上、またはテンキーに対応する仮想キーから発生しました（このキーに複数の可能な位置がある場合）。NumLock キーは常に DOM_KEY_LOCATION_STANDARD の位置でエンコードされるべきであることに注意してください。 |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_right/) | キーのアクティベーションは右側のキー位置から発生しました（このキーに複数の可能な位置がある場合）。 |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_standard/) | キーのアクティベーションは、左または右のバージョンとして区別されてはならず、（NumLock キーを除き）テンキーから、またはテンキーに対応する仮想キーから発生していません。 |

### 参照

* class [UIEvent](../uievent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
