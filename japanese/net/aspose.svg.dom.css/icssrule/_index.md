---
title: "ICSSRule インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css.ICSSRule インターフェイス。CSSRule インターフェイスは、すべての種類の CSS 文の抽象基底インターフェイスです。これにはルールセットと at-rule の両方が含まれます。実装は、パーサーが認識しないルールであっても、CSS スタイルシートで指定されたすべてのルールを保持することが期待されます。認識されないルールは ICSSUnknownRule インターフェイスで表現されます。"
type: docs
weight: 2620
url: /ja/net/aspose.svg.dom.css/icssrule/
---
## ICSSRule interface

CSSRule インターフェイスはあらゆる種類の CSS 文の抽象基底インターフェイスです。これにはルールセットと at-rule の両方が含まれます。実装はパーサーが認識しない場合でも、CSS スタイルシートで指定されたすべてのルールを保持することが期待されます。認識されないルールは ICSSUnknownRule インターフェイスを使用して表されます。

```csharp
public interface ICSSRule
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssrule/csstext/) { get; set; } | ルールの解析可能なテキスト表現です。これはルールの現在の状態を反映し、初期値ではありません。 |
| [ParentRule](../../aspose.svg.dom.css/icssrule/parentrule/) { get; } | このルールが別のルール内に含まれている場合（例: @media ブロック内のスタイルルール）、このプロパティはその包含ルールを返します。ルールが他のルールにネストされていない場合は null を返します。 |
| [ParentStyleSheet](../../aspose.svg.dom.css/icssrule/parentstylesheet/) { get; } | このルールを含むスタイルシートです。 |
| [Type](../../aspose.svg.dom.css/icssrule/type/) { get; } | 上記で定義されたルールのタイプです。バインディング固有のキャストメソッドを使用して、CSSRule インターフェイスのインスタンスから、タイプが示す特定の派生インターフェイスへダウンキャストできることが期待されます。 |

### 参照

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
