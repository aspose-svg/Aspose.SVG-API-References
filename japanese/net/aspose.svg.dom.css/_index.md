---
title: "Aspose.Svg.Dom.Css"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css 名前空間は、すべての CSS 関連操作のためのものです。CSS 公式ドキュメントで指定された CSS プロパティ名と値のペアを中心に扱います。"
type: docs
weight: 90
url: /ja/net/aspose.svg.dom.css/
---
**Aspose.Svg.Dom.Css** 名前空間は、すべての CSS 関連操作のためのものです。CSS 公式文書で指定された CSS プロパティ名と値のペアに集中しています。

## クラス

| クラス | 説明 |
| --- | --- |
| [Counter](./counter/) | Counter インターフェイスは、任意のカウンタまたは counters 関数の値を表すために使用されます。このインターフェイスは、基礎となるスタイルプロパティの値を反映します。 |
| [CSSPrimitiveValue](./cssprimitivevalue/) | CSSPrimitiveValue インターフェイスは単一の CSS 値を表します。このインターフェイスは、ブロック内で現在設定されている特定のスタイルプロパティの値を取得したり、ブロック内で特定のスタイルプロパティを明示的に設定したりするために使用できます。このインターフェイスのインスタンスは、CSSStyleDeclaration インターフェイスの getPropertyCSSValue メソッドから取得できる場合があります。CSSPrimitiveValue オブジェクトは CSS プロパティのコンテキスト内でのみ発生します。 |
| [CSSValue](./cssvalue/) | 単純または複合的な値を表します。CSSValue オブジェクトは CSS プロパティのコンテキスト内でのみ発生します。 |
| [CSSValueList](./cssvaluelist/) | CSSValueList インターフェイスは、CSS 値の順序付けされたコレクションの抽象化を提供します。 |
| [Rect](./rect/) | Rect インターフェイスは任意の rect 値を表すために使用されます。このインターフェイスは基礎となるスタイルプロパティの値を反映します。そのため、CSSPrimitiveValue オブジェクトへの変更はスタイルプロパティを変更します。 |
| [RGBColor](./rgbcolor/) | RGBColor インターフェイスは任意の RGB カラー値を表すために使用されます。このインターフェイスは基礎となるスタイルプロパティの値を反映します。そのため、CSSPrimitiveValue オブジェクトへの変更はスタイルプロパティを変更します。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | 特定の HTML 要素のコンテキストで CSS2 プロパティの設定値操作のためのインターフェイスを提供します。 |
| [ICSSCharsetRule](./icsscharsetrule/) | CSSCharsetRule インターフェイスは CSS スタイルシート内の @charset ルールを表します。encoding 属性の値は DOM オブジェクト内のテキストデータのエンコーディングには影響せず、このエンコーディングは常に UTF-16 です。スタイルシートが読み込まれた後、encoding 属性の値は @charset ルールで見つかった値になります。元のドキュメントに @charset がなかった場合、CSSCharsetRule は作成されません。encoding 属性の値は、スタイルシートのシリアライズ時に使用されるエンコーディングのヒントとしても使用されることがあります。 |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | @counter-style ルールは、作者がカスタムカウンタースタイルを定義できるようにします。 |
| [ICSSFontFaceRule](./icssfontfacerule/) | CSSFontFaceRule インターフェイスは CSS スタイルシート内の @font-face ルールを表します。@font-face ルールはフォント記述のセットを保持するために使用されます。 |
| [ICSSImportRule](./icssimportrule/) | CSSImportRule インターフェイスは CSS スタイルシート内の @import ルールを表します。@import ルールは他のスタイルシートからスタイルルールをインポートするために使用されます。 |
| [ICSSKeyframeRule](./icsskeyframerule/) | CSSKeyframeRule インターフェイスは単一キーのスタイルルールを表します。 |
| [ICSSKeyframesRule](./icsskeyframesrule/) | CSSKeyframesRule インターフェイスは単一アニメーションのキー フレーム全体のセットを表します。 |
| [ICSSMarginRule](./icssmarginrule/) | CSSMarginRule インターフェイスは margin at-rule を表します。 |
| [ICSSMediaRule](./icssmediarule/) | CSSMediaRule インターフェイスは CSS スタイルシート内の @media ルールを表します。@media ルールは特定のメディアタイプ向けのスタイルルールを区切るために使用できます。 |
| [ICSSPageRule](./icsspagerule/) | CSSPageRule インターフェイスは CSS スタイルシート内の @page ルールを表します。@page ルールはページングメディア用のページボックスの寸法、向き、余白などを指定するために使用されます。 |
| [ICSSRule](./icssrule/) | CSSRule インターフェイスはあらゆる種類の CSS 文の抽象基底インターフェイスです。これにはルールセットと at-rule の両方が含まれます。実装はパーサーが認識しない場合でも、CSS スタイルシートで指定されたすべてのルールを保持することが期待されます。認識されないルールは ICSSUnknownRule インターフェイスを使用して表されます。 |
| [ICSSRuleList](./icssrulelist/) | CSSRuleList インターフェイスは CSS ルールの順序付けされたコレクションの抽象化を提供します。 |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | CSSStyleDeclaration インターフェイスは単一の CSS 宣言ブロックを表します。このインターフェイスはブロック内で現在設定されているスタイルプロパティを確認したり、ブロック内でスタイルプロパティを明示的に設定したりするために使用できます。 |
| [ICSSStyleRule](./icssstylerule/) | CSSStyleRule インターフェイスは CSS スタイルシート内の単一のルールセットを表します。 |
| [ICSSStyleSheet](./icssstylesheet/) | CSSStyleSheet インターフェイスは、コンテンツタイプが "text/css" のスタイルシート、すなわち CSS スタイルシートを表す具体的なインターフェイスです。 |
| [ICSSUnknownRule](./icssunknownrule/) | CSSUnknownRule インターフェイスは、このユーザーエージェントがサポートしない at-rule を表します。 |
| [ICSSValueList](./icssvaluelist/) | このインターフェイスは CSS 値の順序付けされたコレクションの抽象化を提供します。 |
| [IDocumentCSS](./idocumentcss/) | このインターフェイスは CSS ビューを持つドキュメントを表します。 |
| [IDocumentStyle](./idocumentstyle/) | DocumentStyle インターフェイスは、ドキュメントに埋め込まれたスタイルシートを取得できるメカニズムを提供します。Document インターフェイスのインスタンスに対してバインディング固有のキャストメソッドを使用することで、DocumentStyle インターフェイスのインスタンスを取得できることが期待されます。 |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | 要素に付随するインラインスタイル情報は style 属性を通じて公開されます。これは HTML 要素（または同様に STYLE 属性を使用する他のスキーマや DTD の要素）の STYLE 属性の内容を表します。 |
| [ILinkStyle](./ilinkstyle/) | LinkStyle インターフェイスは、ドキュメントにリンクされたノードからスタイルシートを取得できるメカニズムを提供します。LinkStyle インターフェイスのインスタンスは、リンクノード（DOM Level 2 の HTMLLinkElement、HTMLStyleElement、または ProcessingInstruction）のインスタンスに対してバインディング固有のキャストメソッドを使用して取得できます。 |
| [IMediaList](./imedialist/) | MediaList インターフェイスは、実装方法を定義または制約せずに、メディアの順序付けされたコレクションの抽象化を提供します。空のリストは、メディア "all" を含むリストと同等です。 |
| [IStyleSheet](./istylesheet/) | StyleSheet インターフェイスは、あらゆるタイプのスタイルシートの抽象基底インターフェイスです。構造化ドキュメントに関連付けられた単一のスタイルシートを表します。 |
| [IStyleSheetList](./istylesheetlist/) | StyleSheetList インターフェイスは、順序付けられたスタイルシートのコレクションの抽象化を提供します。 |
| [IViewCSS](./iviewcss/) | このインターフェイスは CSS ビューを表します。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | CSSEngine モードを指定します。 |
