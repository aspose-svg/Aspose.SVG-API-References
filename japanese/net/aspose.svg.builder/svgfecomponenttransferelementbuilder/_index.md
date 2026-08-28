---
title: "SVGFEComponentTransferElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGFEComponentTransferElementBuilder クラス。SVG フィルターで使用される SVG feComponentTransfer 要素を作成するためのビルダー クラスです。"
type: docs
weight: 1210
url: /ja/net/aspose.svg.builder/svgfecomponenttransferelementbuilder/
---
## SVGFEComponentTransferElementBuilder class

SVG の 'feComponentTransfer' 要素を作成するための Builder クラスで、SVG フィルターで使用されます。

```csharp
public class SVGFEComponentTransferElementBuilder : 
    SVGElementBuilder<SVGFEComponentTransferElement>, ICoreAttributeSetter, 
    IDescriptiveElementBuilder, IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGFEComponentTransferElementBuilder](svgfecomponenttransferelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | 設定されたコンポーネント転送関数を使用して SVGFEComponentTransferElement を構築します。 |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEComponentTransferElement](../../aspose.svg.filters/svgfecomponenttransferelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [WithFeFuncA](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefunca/)(*Action&lt;SVGFEFuncAElementBuilder&gt;*) | アルファチャンネル用に 'feFuncA' コンポーネント転送関数を構成します。 |
| [WithFeFuncB](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefuncb/)(*Action&lt;SVGFEFuncBElementBuilder&gt;*) | 青チャンネル用に 'feFuncB' コンポーネント転送関数を構成します。 |
| [WithFeFuncG](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefuncg/)(*Action&lt;SVGFEFuncGElementBuilder&gt;*) | 緑チャンネル用に 'feFuncG' コンポーネント転送関数を構成します。 |
| [WithFeFuncR](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefuncr/)(*Action&lt;SVGFEFuncRElementBuilder&gt;*) | 赤チャンネル用に 'feFuncR' コンポーネント転送関数を構成します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEComponentTransferElement](../../aspose.svg.filters/svgfecomponenttransferelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
