---
title: "SVGScriptElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGScriptElementBuilder クラス。SVG スクリプト要素を構築するためのビルダー クラスです。スクリプト要素は SVG ドキュメント内に実行可能なスクリプトを埋め込むまたは参照するために使用されます。このクラスは、type、source、cross-origin 設定など、スクリプト要素固有のさまざまな属性を設定するメソッドを提供します。"
type: docs
weight: 1600
url: /ja/net/aspose.svg.builder/svgscriptelementbuilder/
---
## SVGScriptElementBuilder class

SVG の 'script' 要素を構築するためのビルダー クラスです。'script' 要素は SVG ドキュメント内に実行可能なスクリプトを埋め込むまたは参照するために使用されます。このクラスは type、source、cross-origin 設定など、'script' 要素固有のさまざまな属性を設定するメソッドを提供します。

```csharp
public class SVGScriptElementBuilder : SVGElementBuilder<SVGScriptElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGScriptElementBuilder](svgscriptelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGScriptElement](../../aspose.svg/svgscriptelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Crossorigin](../../aspose.svg.builder/svgscriptelementbuilder/crossorigin/)(*string*) | SVG の 'script' 要素の 'crossorigin' 属性を設定し、外部スクリプトの CORS 設定を指定します。 |
| [Href](../../aspose.svg.builder/svgscriptelementbuilder/href/)(*string*) | SVG の 'script' 要素の 'href' 属性を設定し、外部スクリプトファイルの URL を指定します。 |
| [Type](../../aspose.svg.builder/svgscriptelementbuilder/type/)(*string*) | SVG の 'script' 要素の 'type' 属性を設定し、スクリプト言語のタイプを指定します（例: "text/javascript"）。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGScriptElement](../../aspose.svg/svgscriptelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
