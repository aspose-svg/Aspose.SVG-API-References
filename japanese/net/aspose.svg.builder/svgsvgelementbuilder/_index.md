---
title: "SVGSVGElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGSVGElementBuilder クラス。SVG ドキュメントのルート要素である SVGSVGElement を作成するためのビルダー クラスです"
type: docs
weight: 1590
url: /ja/net/aspose.svg.builder/svgsvgelementbuilder/
---
## SVGSVGElementBuilder class

SVG ドキュメントのルート要素である SVGSVGElement を作成するためのビルダー クラスです。

```csharp
public class SVGSVGElementBuilder : SVGElementBuilder<SVGSVGElement>, ICompositeAttributeSetter, 
    ICompositeElementBuilder, IDocumentEventAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter, IViewBoxAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGSVGElementBuilder](svgsvgelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| [BaseProfile](../../aspose.svg.builder/svgsvgelementbuilder/baseprofile/)(*double*) | SVG 要素の 'baseProfile' 属性を設定します。この属性は、ドキュメントに適用される完全な SVG 仕様のどのサブセットかを示します。 |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSVGElement](../../aspose.svg/svgsvgelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ContentScriptType](../../aspose.svg.builder/svgsvgelementbuilder/contentscripttype/)(*string*) | SVG 要素の 'contentScriptType' 属性を設定します。この属性は、SVG ドキュメントの内容に対するデフォルトのスクリプト言語を指定します。 |
| [ContentStyleType](../../aspose.svg.builder/svgsvgelementbuilder/contentstyletype/)(*string*) | SVG 要素の 'contentStyleType' 属性を設定します。この属性は、SVG ドキュメントの内容に対するデフォルトのスタイル言語を指定します。 |
| [Version](../../aspose.svg.builder/svgsvgelementbuilder/version/)(*double*) | SVG 要素の 'version' 属性を設定します。この属性は、ドキュメントが準拠する SVG 仕様のバージョンを指定します。 |
| [WithXlink](../../aspose.svg.builder/svgsvgelementbuilder/withxlink/)() | SVG 要素に XLink 名前空間宣言を追加します。これは、'xlink:href' などの XLink 属性を使用するために必要です。 |
| [ZoomAndPan](../../aspose.svg.builder/svgsvgelementbuilder/zoomandpan/)(*string*) | SVG 要素の 'zoomAndPan' 属性を設定します。この属性は、SVG コンテンツをズームおよびパンできるかどうかを制御します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGSVGElement](../../aspose.svg/svgsvgelement/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IDocumentEventAttributeSetter](../idocumenteventattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
