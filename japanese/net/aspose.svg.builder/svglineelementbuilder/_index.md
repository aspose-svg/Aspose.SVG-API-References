---
title: "SVGLineElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGLineElementBuilder クラス。SVG グラフィック内で直線を描画するために使用される SVG line 要素を構築するビルダー クラス。このクラスは line 要素内のコンテンツ構築を可能にし、SVG の line 要素固有のさまざまな属性を設定するメソッドを提供します。"
type: docs
weight: 1480
url: /ja/net/aspose.svg.builder/svglineelementbuilder/
---
## SVGLineElementBuilder class

SVG の 'line' 要素を構築するためのビルダー クラスで、SVG グラフィック内に直線を描画するために使用されます。'line' 要素内のコンテンツ構築を可能にし、SVG の 'line' 要素固有のさまざまな属性を設定するメソッドを提供します。

```csharp
public class SVGLineElementBuilder : SVGElementBuilder<SVGLineElement>, IAnimationElementBuilder, 
    IDescriptiveElementBuilder, IPaintServerElementBuilder, IShapeAttributeSetter, 
    IShapeContentElementBuilder
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGLineElementBuilder](svglineelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGLineElement](../../aspose.svg/svglineelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [X1](../../aspose.svg.builder/svglineelementbuilder/x1/)(*double, [LengthType](../lengthtype/)*) | SVG の 'line' 要素の 'x1' 属性を設定し、線の開始点の x 座標を指定します。 |
| [X2](../../aspose.svg.builder/svglineelementbuilder/x2/)(*double, [LengthType](../lengthtype/)*) | SVG の 'line' 要素の 'x2' 属性を設定し、線の終了点の x 座標を指定します。 |
| [Y1](../../aspose.svg.builder/svglineelementbuilder/y1/)(*double, [LengthType](../lengthtype/)*) | SVG の 'line' 要素の 'y1' 属性を設定し、線の開始点の y 座標を指定します。 |
| [Y2](../../aspose.svg.builder/svglineelementbuilder/y2/)(*double, [LengthType](../lengthtype/)*) | SVG の 'line' 要素の 'y2' 属性を設定し、線の終点の y 座標を指定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGLineElement](../../aspose.svg/svglineelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeAttributeSetter](../ishapeattributesetter/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
