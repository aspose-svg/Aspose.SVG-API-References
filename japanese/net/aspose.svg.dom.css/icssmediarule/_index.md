---
title: "ICSSMediaRule インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css.ICSSMediaRule インターフェイス。CSSMediaRule インターフェイスは CSS スタイルシート内のメディアルールを表します。メディアルールは特定のメディアタイプ向けのスタイルルールを区切るために使用できます"
type: docs
weight: 2600
url: /ja/net/aspose.svg.dom.css/icssmediarule/
---
## ICSSMediaRule interface

CSSMediaRule インターフェイスは CSS スタイルシート内の @media ルールを表します。@media ルールは特定のメディアタイプ向けのスタイルルールを区切るために使用できます。

```csharp
public interface ICSSMediaRule : ICSSRule
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icssmediarule/cssrules/) { get; } | メディアブロック内に含まれるすべての CSS ルールの一覧です。 |
| [Media](../../aspose.svg.dom.css/icssmediarule/media/) { get; } | このルールのメディアタイプの一覧。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [DeleteRule](../../aspose.svg.dom.css/icssmediarule/deleterule/)(*long*) | メディアブロックからルールを削除するために使用されます。 |
| [InsertRule](../../aspose.svg.dom.css/icssmediarule/insertrule/)(*string, long*) | メディアブロックに新しいルールを挿入するために使用されます。 |

### 参照

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
