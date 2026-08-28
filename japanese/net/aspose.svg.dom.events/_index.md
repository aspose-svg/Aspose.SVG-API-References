---
title: "Aspose.Svg.Dom.Events"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Events 名前空間は、DOM 更新に関連するすべてのイベント用オブジェクトを提供します。イベントに関連付けられた特定のコンテキスト情報の観測へのサブスクリプションや、カスタムイベントの構築を含みます。"
type: docs
weight: 100
url: /ja/net/aspose.svg.dom.events/
---
**Aspose.Svg.Dom.Events** 名前空間は、DOM の更新に関連するあらゆるイベントのオブジェクトを提供します。イベントに関連付けられた特定のコンテキスト情報の観測へのサブスクリプションやカスタムイベントの構築が含まれます。

## クラス

| クラス | 説明 |
| --- | --- |
| [CustomEvent](./customevent/) | CustomEvent インターフェイスを使用したイベントは、カスタムデータを運ぶために使用できます。 |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | 要求されたリソースが利用できない場合、[`DocumentLoadErrorEvent`](../aspose.svg.dom.events/documentloaderrorevent/) が発生します。 |
| [DOMEventHandler](./domeventhandler/) | イベント処理のコールバックを表します。 |
| [ErrorEvent](./errorevent/) | この [`ErrorEvent`](../aspose.svg.dom.events/errorevent/) は、実行時に発生したエラーに関するコンテキスト情報を提供します。 |
| [Event](./event/) | この [`Event`](../aspose.svg.dom.events/event/) は、イベントを処理するハンドラに対して、そのイベントに関するコンテキスト情報を提供するために使用されます。 |
| [FocusEvent](./focusevent/) | FocusEvent インターフェイスは、フォーカスイベントに関連する特定のコンテキスト情報を提供します。 |
| [InputEvent](./inputevent/) | DOM が更新されるたびに、入力イベントが通知として送信されます。 |
| [KeyboardEvent](./keyboardevent/) | KeyboardEvent インターフェイスは、キーボードデバイスに関連する特定のコンテキスト情報を提供します。各キーボードイベントは、値を使用してキーを参照します。キーボードイベントは通常、フォーカスを持つ要素に向けられます。 |
| [MouseEvent](./mouseevent/) | MouseEvent インターフェイスは、マウスイベントに関連する特定のコンテキスト情報を提供します。 |
| [UIEvent](./uievent/) | UIEvent インターフェイスは、ユーザーインターフェイスイベントに関連する特定のコンテキスト情報を提供します。 |
| [WheelEvent](./wheelevent/) | WheelEvent インターフェイスは、ホイールイベントに関連する特定のコンテキスト情報を提供します。WheelEvent インターフェイスのインスタンスを作成するには、WheelEvent コンストラクタを使用し、オプションの WheelEventInit 辞書を渡します。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | この [`IDocumentEvent`](../aspose.svg.dom.events/idocumentevent/) インターフェイスは、ユーザーが実装でサポートされているタイプの [`Event`](../aspose.svg.dom.events/event/) を作成できるメカニズムを提供します。 |
| [IEventListener](./ieventlistener/) | この [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) インターフェイスは、イベント処理の主要な手段です。ユーザーは [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) インターフェイスを実装し、[`AddEventListener`](../aspose.svg.dom/eventtarget/addeventlistener/) メソッドを使用して [`EventTarget`](../aspose.svg.dom/eventtarget/) にリスナーを登録します。リスナーの使用が完了したら、ユーザーはその [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) を [`EventTarget`](../aspose.svg.dom/eventtarget/) から削除すべきです。 |
| [IEventTarget](./ieventtarget/) | DOM イベントモデルをサポートする実装において、すべてのノードは [`EventTarget`](../aspose.svg.dom/eventtarget/) インターフェイスを実装しています。そのため、このインターフェイスは Node インターフェイスのインスタンスに対してバインディング固有のキャストメソッドを使用することで取得できます。このインターフェイスは [`EventTarget`](../aspose.svg.dom/eventtarget/) 上でイベントリスナーの登録と削除を行い、[`IEventTarget`](../aspose.svg.dom.events/ieventtarget/) へイベントをディスパッチすることを可能にします。 |
