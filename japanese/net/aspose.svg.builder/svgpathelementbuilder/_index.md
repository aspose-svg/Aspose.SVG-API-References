---
title: "SVGPathElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGPathElementBuilder クラス。SVG ドキュメント内でパスを定義するために使用される SVG パス要素を構築するビルダー クラスです。このクラスは、パス要素固有のさまざまな属性を設定し、その内容を構築するためのメソッドを提供します。"
type: docs
weight: 1530
url: /ja/net/aspose.svg.builder/svgpathelementbuilder/
---
## SVGPathElementBuilder class

SVG の 'path' 要素を構築するためのビルダー クラスで、SVG ドキュメント内のパスを定義するために使用されます。このクラスは 'path' 要素固有のさまざまな属性を設定するメソッドと、そのコンテンツを構築する機能を提供します。

```csharp
public class SVGPathElementBuilder : SVGElementBuilder<SVGPathElement>, IAnimationElementBuilder, 
    IDescriptiveElementBuilder, IPaintServerElementBuilder, IShapeAttributeSetter, 
    IShapeContentElementBuilder
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGPathElementBuilder](svgpathelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPathElement](../../aspose.svg/svgpathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [D](../../aspose.svg.builder/svgpathelementbuilder/d/)(*Action&lt;PathBuilder&gt;*) | SVG の 'path' 要素の 'd' 属性を設定し、パスの形状を定義します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPathElement](../../aspose.svg/svgpathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeAttributeSetter](../ishapeattributesetter/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
