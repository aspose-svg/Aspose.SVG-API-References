---
title: "ICSSImportRule インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css.ICSSImportRule インターフェイス。CSSImportRule インターフェイスは CSS スタイルシート内のインポートルールを表します。インポートルールは他のスタイルシートからスタイルルールを取り込むために使用されます。"
type: docs
weight: 2560
url: /ja/net/aspose.svg.dom.css/icssimportrule/
---
## ICSSImportRule interface

CSSImportRule インターフェイスは CSS スタイルシート内の @import ルールを表します。@import ルールは他のスタイルシートからスタイルルールをインポートするために使用されます。

```csharp
public interface ICSSImportRule : ICSSRule
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Href](../../aspose.svg.dom.css/icssimportrule/href/) { get; } | インポートされるスタイルシートの場所です。この属性には URI の周囲に \"url(...)\" 指定子は含まれません。 |
| [Media](../../aspose.svg.dom.css/icssimportrule/media/) { get; } | このスタイルシートが使用できるメディアタイプの一覧。 |
| [StyleSheet](../../aspose.svg.dom.css/icssimportrule/stylesheet/) { get; } | このルールが参照するスタイルシートです（ロード済みの場合）。スタイルシートがまだロードされていない、またはロードされない場合（例：ユーザーエージェントがサポートしないメディアタイプ用の場合）、この属性の値は null になります。 |

### 参照

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
