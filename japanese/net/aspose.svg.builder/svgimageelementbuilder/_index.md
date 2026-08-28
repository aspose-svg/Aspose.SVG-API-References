---
title: "SVGImageElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGImageElementBuilder クラス。SVG 画像要素を構築するためのビルダー クラスです。この要素は SVG グラフィック内に画像を埋め込むために使用されます。画像要素固有のさまざまな属性を設定するメソッドや、クリップパス、マスク、スタイル、スクリプトなどの追加構成を追加する機能を提供します。"
type: docs
weight: 1470
url: /ja/net/aspose.svg.builder/svgimageelementbuilder/
---
## SVGImageElementBuilder class

SVG の 'image' 要素を構築するためのビルダー クラスです。この要素は SVG グラフィック内に画像を埋め込むために使用されます。'image' 要素固有のさまざまな属性を設定するメソッドや、クリップパス、マスク、スタイル、スクリプトなどの追加設定を追加する機能を提供します。

```csharp
public class SVGImageElementBuilder : SVGElementBuilder<SVGImageElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGImageElementBuilder](svgimageelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddClipPath](../../aspose.svg.builder/svgimageelementbuilder/addclippath/)(*Action&lt;SVGClipPathElementBuilder&gt;*) | SVG の 'image' 要素にクリップパス構成を追加します。 |
| [AddMask](../../aspose.svg.builder/svgimageelementbuilder/addmask/)(*Action&lt;SVGMaskElementBuilder&gt;*) | SVG の 'image' 要素にマスク構成を追加します。 |
| [AddScript](../../aspose.svg.builder/svgimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG の 'image' 要素にスクリプト構成を追加します。 |
| [AddStyle](../../aspose.svg.builder/svgimageelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG の 'image' 要素にスタイル構成を追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGImageElement](../../aspose.svg/svgimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgimageelementbuilder/href/)(*string*) | SVG の 'image' 要素の 'href' 属性を設定し、埋め込む画像の URL を指定します。 |
| [HrefBase64FromBytes](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64frombytes/)(*byte[], string*) | SVG の 'image' 要素の 'href' 属性を、画像の Base64 エンコードされたバイトで設定します。 |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile)(*string*) | SVG の 'image' 要素の 'href' 属性を、Base64 エンコードされた画像ファイルで設定します。 |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile_1)(*string, string*) | SVG の 'image' 要素の 'href' 属性を、指定された MIME タイプの Base64 エンコード画像ファイルで設定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGImageElement](../../aspose.svg/svgimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
