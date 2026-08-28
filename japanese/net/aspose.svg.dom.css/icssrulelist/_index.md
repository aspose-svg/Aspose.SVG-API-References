---
title: "ICCSSRuleList インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css.ICSSRuleList インターフェイス。CSSRuleList インターフェイスは CSS ルールの順序付けられたコレクションの抽象化を提供します。"
type: docs
weight: 2630
url: /ja/net/aspose.svg.dom.css/icssrulelist/
---
## ICSSRuleList interface

CSSRuleList インターフェイスは CSS ルールの順序付けされたコレクションの抽象化を提供します。

```csharp
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Item](../../aspose.svg.dom.css/icssrulelist/item/) { get; } | メソッド item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList) を使用して CSS ルールを取得します。このコレクション内の順序は CSS スタイルシート内のルールの順序を表します。インデックスがリスト内のルール数以上の場合、null を返します。 |
| [Length](../../aspose.svg.dom.css/icssrulelist/length/) { get; } | リスト内の CSSRules の数です。有効な子ルールインデックスの範囲は 0 から length-1 まで（両端含む）です。 |

### 参照

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
