---
title: "SVGStopElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGStopElementBuilder クラス。SVG の stop 要素を構築するためのビルダー クラスです。stop 要素は、線形または放射状のグラデーション定義内でカラー ストップを定義するために使用されます。このクラスは、offset や color など、stop 要素固有のさまざまな属性を設定するメソッドを提供します。"
type: docs
weight: 1620
url: /ja/net/aspose.svg.builder/svgstopelementbuilder/
---
## SVGStopElementBuilder class

SVG の 'stop' 要素を構築するためのビルダー クラスです。'stop' 要素は（線形または放射状）グラデーション定義内で色止点を定義するために使用されます。このクラスはオフセットや色など、'stop' 要素固有のさまざまな属性を設定するメソッドを提供します。

```csharp
public class SVGStopElementBuilder : SVGElementBuilder<SVGStopElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGStopElementBuilder](svgstopelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgstopelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG の 'stop' 要素にスクリプト構成を追加します。 |
| [AddStyle](../../aspose.svg.builder/svgstopelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG の 'stop' 要素にスタイル構成を追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStopElement](../../aspose.svg/svgstopelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Offset](../../aspose.svg.builder/svgstopelementbuilder/offset/)(*double, [StopUnitType](../stopunittype/)*) | SVG の 'stop' 要素の 'offset' 属性を設定し、グラデーション内のカラー ストップの位置を指定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStopElement](../../aspose.svg/svgstopelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
