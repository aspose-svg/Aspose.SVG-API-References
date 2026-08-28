---
title: "ICSSCharsetRule インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css.ICSSCharsetRule インターフェイス。CSSCharsetRule インターフェイスは CSS スタイルシート内の文字セットルールを表します。encoding 属性の値は DOM オブジェクト内のテキストデータのエンコーディングに影響せず、このエンコーディングは常に UTF-16 です。スタイルシートがロードされた後、encoding 属性の値は文字セットルールで見つかった値になります。元のドキュメントに文字セットが無い場合、CSSCharsetRule は作成されません。encoding 属性の値は、スタイルシートのシリアライズ時に使用されるエンコーディングのヒントとしても使用されることがあります。"
type: docs
weight: 2530
url: /ja/net/aspose.svg.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

CSSCharsetRule インターフェイスは CSS スタイルシート内の @charset ルールを表します。encoding 属性の値は DOM オブジェクト内のテキストデータのエンコーディングには影響せず、このエンコーディングは常に UTF-16 です。スタイルシートが読み込まれた後、encoding 属性の値は @charset ルールで見つかった値になります。元のドキュメントに @charset がなかった場合、CSSCharsetRule は作成されません。encoding 属性の値は、スタイルシートのシリアライズ時に使用されるエンコーディングのヒントとしても使用されることがあります。

```csharp
public interface ICSSCharsetRule : ICSSRule
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Encoding](../../aspose.svg.dom.css/icsscharsetrule/encoding/) { get; set; } | この @charset ルールで使用されるエンコーディング情報。 |

### 参照

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
