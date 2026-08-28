---
title: "SVGFESpecularLightingElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGFESpecularLightingElementBuilder クラス。画像に鏡面照明効果を適用する SVG feSpecularLighting 要素を作成するためのビルダー クラスです。"
type: docs
weight: 1400
url: /ja/net/aspose.svg.builder/svgfespecularlightingelementbuilder/
---
## SVGFESpecularLightingElementBuilder class

SVG の 'feSpecularLighting' 要素を作成するための Builder クラスで、画像に鏡面照明効果を適用します。

```csharp
public class SVGFESpecularLightingElementBuilder : 
    SVGFEBaseLightingElementBuilder<SVGFESpecularLightingElement, SVGFESpecularLightingElementBuilder>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGFESpecularLightingElementBuilder](svgfespecularlightingelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) |  |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFESpecularLightingElement](../../aspose.svg.filters/svgfespecularlightingelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [KernelUnitLength](../../aspose.svg.builder/svgfespecularlightingelementbuilder/kernelunitlength/)(*double, double?*) | 畳み込みカーネルの単位長さを定義する 'kernelUnitLength' 属性を設定します。 |
| [SpecularConstant](../../aspose.svg.builder/svgfespecularlightingelementbuilder/specularconstant/)(*double*) | 鏡面反射定数を表す 'specularConstant' 属性を設定します。 |
| [SpecularExponent](../../aspose.svg.builder/svgfespecularlightingelementbuilder/specularexponent/)(*double*) | 鏡面ハイライトを制御する 'specularExponent' 属性を設定します。 |
| [SurfaceScale](../../aspose.svg.builder/svgfespecularlightingelementbuilder/surfacescale/)(*double*) | 照明計算のための表面の高さを定義する feSpecularLighting 要素の 'surfaceScale' 属性を設定します。 |
| [WithFeDistantLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfedistantlight/)(*Action&lt;SVGFEDistantLightElementBuilder&gt;*) |  |
| [WithFePointLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfepointlight/)(*Action&lt;SVGFEPointLightElementBuilder&gt;*) |  |
| [WithFeSpotLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfespotlight/)(*Action&lt;SVGFESpotLightElementBuilder&gt;*) |  |

### 参照

* class [SVGFEBaseLightingElementBuilder&lt;TElement,TBuilder&gt;](../svgfebaselightingelementbuilder-2/)
* class [SVGFESpecularLightingElement](../../aspose.svg.filters/svgfespecularlightingelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
