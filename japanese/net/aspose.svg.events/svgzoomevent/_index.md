---
title: "SVGZoomEvent クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Events.SVGZoomEvent クラス。ユーザーが操作を開始し、SVG ドキュメントフラグメントの現在のビューが再スケールされるとズームイベントが発生します。イベントハンドラは svg 要素でのみ認識されます。"
type: docs
weight: 3710
url: /ja/net/aspose.svg.events/svgzoomevent/
---
## SVGZoomEvent class

ズーム イベントは、ユーザーが操作を開始し、SVG ドキュメント フラグメントの現在のビューが再スケーリングされると発生します。イベントハンドラは ‘svg’ 要素でのみ認識されます。

```csharp
public class SVGZoomEvent : Event
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | イベントがバブリングイベントかどうかを示すために使用します。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | イベントのデフォルトアクションを防止できるかどうかを示すために使用します。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | 現在処理中の [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) を持つ [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) を示すために使用されます。キャプチャおよびバブリング時に特に有用です。 |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | 現在評価されているイベントフローのフェーズを示すために使用します。 |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted 属性は初期化された値を返す必要があります。イベント作成時にこの属性は false に初期化されます。 |
| [NewScale](../../aspose.svg.events/svgzoomevent/newscale/) { get; } | ズーム操作が処理された後に適用されるスケール係数です。 |
| [NewTranslate](../../aspose.svg.events/svgzoomevent/newtranslate/) { get; } | ズーム操作が処理された後に適用される平行移動値です。SVGPoint オブジェクトは読み取り専用です。 |
| [PreviousScale](../../aspose.svg.events/svgzoomevent/previousscale/) { get; } | ズーム操作が発生する前に設定されていた、以前のズーム操作からのスケール係数です。 |
| [PreviousTranslate](../../aspose.svg.events/svgzoomevent/previoustranslate/) { get; } | ズーム操作が発生する前に設定されていた、以前のズーム操作からの平行移動値です。SVGPoint オブジェクトは読み取り専用です。 |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | イベントが元々ディスパッチされた ``[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)`` を示すために使用されます。 |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | イベントが作成された時刻（エポックからのミリ秒）を指定するために使用します。一部のシステムがこの情報を提供しない場合、timeStamp の値はすべてのイベントで利用できないことがあります。利用できない場合は 0 が返されます。エポック時刻の例としてはシステム起動時や 1970年1月1日 0:0:0 UTC があります。 |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | イベントの名前（大文字小文字を区別しません）。名前は XML 名である必要があります。 |
| [ZoomRectScreen](../../aspose.svg.events/svgzoomevent/zoomrectscreen/) { get; } | 画面単位で指定されたズーム矩形です。SVGRect オブジェクトは読み取り専用です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | ``[`InitEvent`](../../aspose.svg.dom.events/event/initevent/)`` メソッドは、``[`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/)`` インターフェイスを介して作成された ``[`Event`](../../aspose.svg.dom.events/event/)`` の値を初期化するために使用されます。 |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、``[`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/)`` メソッドは、イベントがキャンセルされることを示すために使用されます。これにより、実装が通常イベントの結果として行うデフォルトの動作は実行されません。 |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、現在のリスナーの後に登録されたイベントリスナーにイベントが到達するのを防ぎ、ツリー内でディスパッチされた場合は他のオブジェクトへの到達も防止します。 |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | ``[`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/)`` メソッドは、イベントフロー中にイベントのさらなる伝播を防止するために使用されます。 |

### 参照

* class [Event](../../aspose.svg.dom.events/event/)
* namespace [Aspose.Svg.Events](../../aspose.svg.events/)
* assembly [Aspose.SVG](../../)
