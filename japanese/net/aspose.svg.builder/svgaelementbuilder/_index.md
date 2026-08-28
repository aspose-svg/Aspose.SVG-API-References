---
title: "SVGAElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGAElementBuilder クラス。ハイパーリンクを定義するために使用される SVG の a 要素を構築するビルダー クラスです。要素内のコンテンツ構築を可能にし、SVG の a 要素に固有のさまざまな属性を設定するメソッドを提供します。"
type: docs
weight: 1070
url: /ja/net/aspose.svg.builder/svgaelementbuilder/
---
## SVGAElementBuilder class

ハイパーリンクを定義するために使用される SVG の 'a' 要素を構築するビルダー クラスです。'a' 要素内のコンテンツ構築を可能にし、SVG の 'a' 要素固有のさまざまな属性を設定するメソッドを提供します。

```csharp
public class SVGAElementBuilder : SVGElementBuilder<SVGAElement>, ICompositeAttributeSetter, 
    ICompositeElementBuilder
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGAElementBuilder](svgaelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGAElement](../../aspose.svg/svgaelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Download](../../aspose.svg.builder/svgaelementbuilder/download/)(*string*) | SVG の 'a' 要素の 'download' 属性を設定し、リンクがアクティブ化されたときにダウンロードされることを示します。 |
| [Href](../../aspose.svg.builder/svgaelementbuilder/href/)(*string*) | SVG の 'a' 要素の 'href' 属性を設定し、リンクされたリソースの URL を指定します。 |
| [HrefLang](../../aspose.svg.builder/svgaelementbuilder/hreflang/)(*string*) | SVG の 'a' 要素の 'hreflang' 属性を設定し、リンクされたリソースの言語を示します。 |
| [Ping](../../aspose.svg.builder/svgaelementbuilder/ping/)(*string*) | SVG の 'a' 要素の 'ping' 属性を設定し、リンクがたどられた場合に通知される URL のリストを含めます。 |
| [ReferrerPolicy](../../aspose.svg.builder/svgaelementbuilder/referrerpolicy/)(*[ReferrerPolicy](../referrerpolicy/)*) | SVG の 'a' 要素の 'referrerPolicy' 属性を設定し、リクエストと共に送信するリファラの量を指定します。 |
| [Rel](../../aspose.svg.builder/svgaelementbuilder/rel/)(*string*) | SVG の 'a' 要素の 'rel' 属性を設定し、ターゲットオブジェクトとリンクオブジェクトの関係を指定します。 |
| [SetTarget](../../aspose.svg.builder/svgaelementbuilder/settarget/)(*string*) | SVG の 'a' 要素の 'target' 属性をカスタム XML 名に設定します。 |
| [Type](../../aspose.svg.builder/svgaelementbuilder/type/)(*string*) | SVG の 'a' 要素の 'type' 属性を設定し、リンクされたリソースのメディアタイプを指定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGAElement](../../aspose.svg/svgaelement/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
