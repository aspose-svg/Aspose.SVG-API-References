---
title: "SVGStyleElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGStyleElementBuilder クラス。SVGスタイル要素を構築するためのビルダー クラスです。このクラスは、CSS ルールを使用した SVG スタイル要素の作成と構成を支援します。"
type: docs
weight: 1630
url: /ja/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

SVG の 'style' 要素を構築するためのビルダー クラスです。このクラスは CSS ルールを持つ SVG スタイル要素の作成と設定を支援します。

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | スタイルコンテンツにコメントを追加します。 |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | RuleBuilder を使用してスタイル要素に CSS ルールを追加します。 |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | スタイル要素に CSS ルールを追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | 蓄積された CSS ルールで SVG スタイル要素を構築し、指定されたドキュメントに追加します。 |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | SVG の 'style' 要素の 'media' 属性を設定します。この属性は、スタイルが対象とするメディアを指定し、メディアタイプに応じて条件付きにすることができます。 |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | SVG の 'style' 要素の 'title' 属性を設定します。この属性はスタイル要素に助言的なタイトルを提供し、アクセシビリティやツールチップテキストに役立ちます。 |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | SVG の 'style' 要素の 'type' 属性を設定します。この属性は要素の内容のスタイルシート言語を指定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
