---
title: "IUserAgentService インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Services.IUserAgentService インターフェイス。ユーザーエージェント環境を記述するインターフェイスです。"
type: docs
weight: 5870
url: /ja/net/aspose.svg.services/iuseragentservice/
---
## IUserAgentService interface

ユーザーエージェント環境を記述したインターフェイスです。

```csharp
public interface IUserAgentService
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CharSet](../../aspose.svg.services/iuseragentservice/charset/) { get; set; } | ドキュメントの主要文字セットを取得または設定します。 |
| [CSSEngineMode](../../aspose.svg.services/iuseragentservice/cssenginemode/) { get; set; } | CSS エンジンが動作するモードを取得または設定します。 |
| [FontsSettings](../../aspose.svg.services/iuseragentservice/fontssettings/) { get; } | !:Html.FontsSettings オブジェクトを取得します。このオブジェクトはフォント処理の設定に使用されます。 |
| [Language](../../aspose.svg.services/iuseragentservice/language/) { get; set; } | [`Language`](./language/) は要素の内容およびテキストを含む属性の主要言語を指定します。その値は有効な BCP 47 言語タグ、または空文字列である必要があります。属性を空文字列に設定すると、主要言語が不明であることを示します。 |
| [ShowImagePlaceholders](../../aspose.svg.services/iuseragentservice/showimageplaceholders/) { get; set; } | 画像はフォールバックコンテンツを持つことができます。外部リソースが使用できない場合（例: サポートされていない形式の場合）に使用すべきコンテンツです。プロパティ [`ShowImagePlaceholders`](./showimageplaceholders/) はフォールバック画像を表示するかどうかを指定します（デフォルトは true）。 |
| [UserStyleSheet](../../aspose.svg.services/iuseragentservice/userstylesheet/) { get; set; } | 特定のドキュメントのスタイル情報を指定できます。 |

### 参照

* namespace [Aspose.Svg.Services](../../aspose.svg.services/)
* assembly [Aspose.SVG](../../)
