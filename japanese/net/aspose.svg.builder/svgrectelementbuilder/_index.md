---
title: "SVGRectElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGRectElementBuilder クラス。SVG の rect 要素を構築するためのビルダー クラスです。rect 要素は SVG グラフィック内で矩形を作成するために使用されます。このクラスは、角の半径やサイズなど、rect 要素固有のさまざまな属性を設定するメソッドを提供します。"
type: docs
weight: 1580
url: /ja/net/aspose.svg.builder/svgrectelementbuilder/
---
## SVGRectElementBuilder class

SVG の 'rect' 要素を構築するためのビルダー クラスです。'rect' 要素は SVG グラフィック内に矩形を作成するために使用されます。このクラスはコーナー半径や寸法を含む、'rect' 要素固有のさまざまな属性を設定するメソッドを提供します。

```csharp
public class SVGRectElementBuilder : SVGElementBuilder<SVGRectElement>, IAnimationElementBuilder, 
    IDescriptiveElementBuilder, IPaintServerElementBuilder, IRectAttributeSetter, 
    IShapeAttributeSetter, IShapeContentElementBuilder
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGRectElementBuilder](svgrectelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGRectElement](../../aspose.svg/svgrectelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Rx](../../aspose.svg.builder/svgrectelementbuilder/rx/)(*double, [LengthType](../lengthtype/)*) | SVG の 'rect' 要素の 'rx' 属性を設定し、矩形の角丸の水平半径を指定します。 |
| [Ry](../../aspose.svg.builder/svgrectelementbuilder/ry/)(*double, [LengthType](../lengthtype/)*) | SVG の 'rect' 要素の 'ry' 属性を設定し、矩形の角丸の垂直半径を指定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGRectElement](../../aspose.svg/svgrectelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IShapeAttributeSetter](../ishapeattributesetter/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
