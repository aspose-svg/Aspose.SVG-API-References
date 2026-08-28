---
title: "FontMatcher.MatchFontFallback"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "FontMatcher MatchFontFallback メソッド。このメソッドはフォント検索フォルダーで適切なフォントが見つからない場合に呼び出されます。fontMatchingProperties に基づいて charCode をレンダリングできる TrueType フォントを返すか、利用可能なフォントがない場合は null を返す必要があります。"
type: docs
weight: 10
url: /ja/net/aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

フォント検索フォルダーに適切なフォントが見つからない場合にこのメソッドが呼び出されます。*fontMatchingProperties* に基づいて *charCode* をレンダリングできる真のタイプのフォントを返すか、該当フォントが利用できない場合は `null` を返す必要があります。

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    int charCode)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | マッチしたフォントのプロパティ。 |
| charCode | Int32 | マッチしたフォントでレンダリングされる文字のコード。 |

### 戻り値

フォントデータを含むバイト配列、または `null`。

### 参照

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* namespace [Aspose.Svg.Rendering.Fonts](../../../aspose.svg.rendering.fonts/)
* assembly [Aspose.SVG](../../../)
