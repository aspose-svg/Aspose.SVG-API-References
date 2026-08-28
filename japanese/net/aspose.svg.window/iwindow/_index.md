---
title: "IWindow インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Window.IWindow インターフェイス。window オブジェクトは DOM ドキュメントを含むウィンドウを表します。"
type: docs
weight: 5920
url: /ja/net/aspose.svg.window/iwindow/
---
## IWindow interface

window オブジェクトは、DOM ドキュメントを含むウィンドウを表します。

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document/) { get; } | document 属性は Window オブジェクトの最新の Document オブジェクトを返す必要があります。 |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement/) { get; } | Document の frameElement オブジェクトです。 |
| [LocalStorage](../../aspose.svg.window/iwindow/localstorage/) { get; } | ユーザーエージェントにキー/バリューのペアを保存できる Storage オブジェクトを返します。 |
| [Location](../../aspose.svg.window/iwindow/location/) { get; } | Window インターフェイスの location 属性は、その Window オブジェクトの Document に対する Location オブジェクトを返す必要があります。 |
| [Name](../../aspose.svg.window/iwindow/name/) { get; set; } | Window オブジェクトの name 属性は、取得時に現在のブラウジングコンテキストの名前を返し、設定時にはブラウジングコンテキストの名前を新しい値に設定しなければなりません。 |
| [Opener](../../aspose.svg.window/iwindow/opener/) { get; } | Window オブジェクトの opener IDL 属性は、取得時に、現在のブラウジングコンテキストが作成された元のブラウジングコンテキスト（その opener ブラウジングコンテキスト）の WindowProxy オブジェクトが存在し、かつ利用可能で、かつ現在のブラウジングコンテキストがその opener を放棄していない場合にそれを返す必要があります。そうでない場合は null を返さなければなりません。設定時に新しい値が null の場合、現在のブラウジングコンテキストはその opener を放棄しなければなりません。新しい値がそれ以外の場合、ユーザーエージェントは Window オブジェクトの [[DefineOwnProperty]] 内部メソッドを呼び出し、プロパティ名 \"opener\" をプロパティキーとして、プロパティ記述子 { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } を渡し、ここで value は新しい値です。 |
| [Parent](../../aspose.svg.window/iwindow/parent/) { get; } | ブラウジングコンテキスト b 内の Document の Window オブジェクトの parent IDL 属性は、親ブラウジングコンテキストが存在する場合（すなわち b が子ブラウジングコンテキストである場合）にはその WindowProxy オブジェクトを返し、存在しない場合（すなわちトップレベルのブラウジングコンテキストまたは分離された入れ子ブラウジングコンテキストである場合）にはコンテキスト b 自身の WindowProxy オブジェクトを返さなければなりません。 |
| [Self](../../aspose.svg.window/iwindow/self/) { get; } | Window オブジェクトのブラウジングコンテキストの WindowProxy オブジェクトを返します。 |
| [Top](../../aspose.svg.window/iwindow/top/) { get; } | ブラウジングコンテキスト b 内の Document の Window オブジェクトの top IDL 属性は、トップレベルのブラウジングコンテキストが存在する場合（それがトップレベルのブラウジングコンテキストであればその自身の WindowProxy オブジェクトになります）にはその WindowProxy オブジェクトを返し、存在しない場合（例：分離された入れ子ブラウジングコンテキストである場合）には自身の WindowProxy オブジェクトを返さなければなりません。 |
| [Window](../../aspose.svg.window/iwindow/window/) { get; } | Window オブジェクトのブラウジングコンテキストの WindowProxy オブジェクトを返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert/)(*string*) | 指定されたメッセージでモーダルアラートを表示し、ユーザーがそれを閉じるまで待機します。 |
| [Atob](../../aspose.svg.window/iwindow/atob/)(*string*) | 入力データを、Base64 エンコードされたバイナリデータを含む Unicode 文字列の形で受け取り、デコードし、U+0000 から U+00FF の範囲の文字で構成された文字列を返します。各文字はそれぞれ 0x00 から 0xFF の値を持つバイナリバイトを表します。 |
| [Btoa](../../aspose.svg.window/iwindow/btoa/)(*string*) | 入力データを、U+0000 から U+00FF の範囲の文字のみを含む Unicode 文字列の形で受け取り、各文字が 0x00 から 0xFF のバイナリバイトを表すものとして、Base64 表現に変換し、返します。 |
| [Confirm](../../aspose.svg.window/iwindow/confirm/)(*string*) | 指定されたメッセージでモーダルの OK/Cancel プロンプトを表示し、ユーザーがそれを閉じるまで待機し、ユーザーが OK をクリックした場合は true、Cancel をクリックした場合は false を返します。 |
| [MatchMedia](../../aspose.svg.window/iwindow/matchmedia/)(*string*) | 新しい MediaQueryList オブジェクトを返します。このオブジェクトは、ドキュメントがメディアクエリ文字列に一致するかどうかを判定したり、その一致（または不一致）を検出するためにドキュメントを監視したりするのに使用できます。CSSOM View Module 仕様を参照してください: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [Prompt](../../aspose.svg.window/iwindow/prompt/)(*string, string*) | 指定されたメッセージでモーダルのテキストフィールドプロンプトを表示し、ユーザーがそれを閉じるまで待機し、ユーザーが入力した値を返します。ユーザーがプロンプトをキャンセルした場合は null を返します。第2引数が存在する場合、与えられた値がデフォルトとして使用されます。 |

### 参照

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
