---
title: "SVGTSpanElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGTSpanElementBuilder クラス。SVGTSpanElement を作成するためのビルダー クラスで、SVG ドキュメント内でテキストの位置指定とスタイル設定に使用されます。"
type: docs
weight: 1660
url: /ja/net/aspose.svg.builder/svgtspanelementbuilder/
---
## SVGTSpanElementBuilder class

SVGドキュメント内でテキストの位置付けとスタイル設定に使用されるSVGTSpanElementを作成するためのビルダー クラスです。

```csharp
public class SVGTSpanElementBuilder : SVGElementBuilder<SVGTSpanElement>, 
    IBaseAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IPaintServerElementBuilder, ITextContentPositioningAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGTSpanElementBuilder](svgtspanelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtspanelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | 現在の tspan 要素にアンカー (a) 要素を追加します。 |
| [AddScript](../../aspose.svg.builder/svgtspanelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 現在の tspan 要素に script 要素を追加します。 |
| [AddStyle](../../aspose.svg.builder/svgtspanelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | 現在の tspan 要素に style 要素を追加します。 |
| [AddTSpan](../../aspose.svg.builder/svgtspanelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | 現在の tspan 要素に入れ子の tspan 要素を追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTSpanElement](../../aspose.svg/svgtspanelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGTSpanElement](../../aspose.svg/svgtspanelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../itextcontentpositioningattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
