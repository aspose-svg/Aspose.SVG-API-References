---
title: "IStyleSheet インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css.IStyleSheet インターフェイス。StyleSheet インターフェイスはすべてのタイプのスタイルシートの抽象基底インターフェイスです。構造化ドキュメントに関連付けられた単一のスタイルシートを表します。"
type: docs
weight: 2740
url: /ja/net/aspose.svg.dom.css/istylesheet/
---
## IStyleSheet interface

StyleSheet インターフェイスは、あらゆるタイプのスタイルシートの抽象基底インターフェイスです。構造化ドキュメントに関連付けられた単一のスタイルシートを表します。

```csharp
public interface IStyleSheet
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Disabled](../../aspose.svg.dom.css/istylesheet/disabled/) { get; set; } | スタイルシートがドキュメントに適用されている場合は false、適用されていない場合は true です。この属性を変更すると、ドキュメントのスタイルの再解決が発生する可能性があります。スタイルシートは、適切なメディア定義が存在し、かつ disabled 属性が false の場合にのみ適用されます。そのため、メディアが現在のユーザーエージェントに適用されない場合、disabled 属性は無視されます。 |
| [Href](../../aspose.svg.dom.css/istylesheet/href/) { get; } | スタイルシートがリンクされたスタイルシートの場合、その属性の値はその場所です。インラインスタイルシートの場合、この属性の値は null です。 |
| [Media](../../aspose.svg.dom.css/istylesheet/media/) { get; } | スタイル情報の対象となるメディアです。 |
| [OwnerNode](../../aspose.svg.dom.css/istylesheet/ownernode/) { get; } | このスタイルシートをドキュメントに関連付けるノードです。HTML の場合、対応する LINK または STYLE 要素になることがあります。XML の場合、リンク処理命令になることがあります。他のスタイルシートにインクルードされているスタイルシートの場合、この属性の値は null です。 |
| [ParentStyleSheet](../../aspose.svg.dom.css/istylesheet/parentstylesheet/) { get; } | スタイルシートのインクルード概念をサポートする言語では、この属性は包含するスタイルシート（存在する場合）を表します。スタイルシートがトップレベルの場合、または言語がインクルードをサポートしない場合、この属性の値は null です。 |
| [Title](../../aspose.svg.dom.css/istylesheet/title/) { get; } | 助言的なタイトルです。 |
| [Type](../../aspose.svg.dom.css/istylesheet/type/) { get; } | これはこのスタイルシートのスタイルシート言語を指定します。スタイルシート言語はコンテンツタイプとして指定されます（例: "text/css"）。 |

### 参照

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
