---
title: "SVGTextPathElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGTextPathElementBuilder クラス。テキストをパスに合わせて配置するために使用される SVG textPath 要素を作成するビルダー クラスです。"
type: docs
weight: 1680
url: /ja/net/aspose.svg.builder/svgtextpathelementbuilder/
---
## SVGTextPathElementBuilder class

テキストをパスに合わせて配置するために使用される SVG の 'textPath' 要素を作成するビルダー クラスです。

```csharp
public class SVGTextPathElementBuilder : SVGElementBuilder<SVGTextPathElement>, 
    IBaseAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IPaintServerElementBuilder, IShapeContentElementBuilder, ITextContentSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGTextPathElementBuilder](svgtextpathelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtextpathelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | 'textPath' に 'a'（アンカー）要素の構成を追加します。 |
| [AddTSpan](../../aspose.svg.builder/svgtextpathelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | 'textPath' に 'tspan' 要素の構成を追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTextPathElement](../../aspose.svg/svgtextpathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgtextpathelementbuilder/href/)(*string*) | パス要素への参照を指定する 'href' 属性を設定します。 |
| [LengthAdjust](../../aspose.svg.builder/svgtextpathelementbuilder/lengthadjust/)(*[LengthAdjust](../lengthadjust/)*) | テキスト長さの調整方法を指定する 'lengthAdjust' 属性を設定します。 |
| [Method](../../aspose.svg.builder/svgtextpathelementbuilder/method/)(*[TextPathMethod](../textpathmethod/)*) | パスに沿ったテキスト配置方法を指定する 'method' 属性を設定します。 |
| [Path](../../aspose.svg.builder/svgtextpathelementbuilder/path/)(*Action&lt;PathBuilder&gt;*) | テキスト用のパスを構成します。 |
| [Side](../../aspose.svg.builder/svgtextpathelementbuilder/side/)(*[HorizontalEdge](../horizontaledge/)*) | テキストが配置されるパスの側面を指定する 'side' 属性を設定します。 |
| [Spacing](../../aspose.svg.builder/svgtextpathelementbuilder/spacing/)(*[TextPathSpacing](../textpathspacing/)*) | パスに沿ったテキストの間隔戦略を指定する 'spacing' 属性を設定します。 |
| [StartOffset](../../aspose.svg.builder/svgtextpathelementbuilder/startoffset/)(*double, [LengthType](../lengthtype/)*) | パス上のテキストの開始位置を指定する 'startOffset' 属性を設定します。 |
| [TextLength](../../aspose.svg.builder/svgtextpathelementbuilder/textlength/)(*double, [LengthType](../lengthtype/)*) | テキストの長さを指定する 'textLength' 属性を設定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGTextPathElement](../../aspose.svg/svgtextpathelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* interface [ITextContentSetter](../itextcontentsetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
