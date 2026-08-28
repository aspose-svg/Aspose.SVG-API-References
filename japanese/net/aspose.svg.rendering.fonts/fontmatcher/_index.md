---
title: "FontMatcher クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Rendering.Fonts.FontMatcher クラス。このクラスはフォントマッチング アルゴリズムの一部を制御できるようにします"
type: docs
weight: 4850
url: /ja/net/aspose.svg.rendering.fonts/fontmatcher/
---
## FontMatcher class

このクラスは、フォントマッチングアルゴリズムの一部を制御できるようにします。

```csharp
public abstract class FontMatcher
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [MatchFontFallback](../../aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/)(*[FontMatchingProperties](../fontmatchingproperties/), int*) | フォント検索フォルダーに適切なフォントが見つからない場合にこのメソッドが呼び出されます。*fontMatchingProperties* に基づいて *charCode* をレンダリングできる真のタイプのフォントを返すか、該当フォントが利用できない場合は `null` を返す必要があります。 |

### 参照

* namespace [Aspose.Svg.Rendering.Fonts](../../aspose.svg.rendering.fonts/)
* assembly [Aspose.SVG](../../)
