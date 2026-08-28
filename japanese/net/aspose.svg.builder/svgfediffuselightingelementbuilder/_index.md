---
title: "SVGFEDiffuseLightingElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGFEDiffuseLightingElementBuilder クラス。SVG フィルターで使用され、拡散照明効果を適用するための SVG feDiffuseLighting 要素を作成するビルダー クラス"
type: docs
weight: 1240
url: /ja/net/aspose.svg.builder/svgfediffuselightingelementbuilder/
---
## SVGFEDiffuseLightingElementBuilder class

SVG の 'feDiffuseLighting' 要素を作成するための Builder クラスで、拡散照明効果を適用する SVG フィルターで使用されます。

```csharp
public class SVGFEDiffuseLightingElementBuilder : 
    SVGFEBaseLightingElementBuilder<SVGFEDiffuseLightingElement, SVGFEDiffuseLightingElementBuilder>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGFEDiffuseLightingElementBuilder](svgfediffuselightingelementbuilder/)() | デフォルトコンストラクタです。 |

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
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEDiffuseLightingElement](../../aspose.svg.filters/svgfediffuselightingelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [DiffuseConstant](../../aspose.svg.builder/svgfediffuselightingelementbuilder/diffuseconstant/)(*double*) | feDiffuseLighting 要素の 'diffuseConstant' 属性を設定します。 |
| [KernelUnitLength](../../aspose.svg.builder/svgfediffuselightingelementbuilder/kernelunitlength/)(*double, double?*) | feDiffuseLighting 要素の 'kernelUnitLength' 属性を設定します。 |
| [SurfaceScale](../../aspose.svg.builder/svgfediffuselightingelementbuilder/surfacescale/)(*double*) | feDiffuseLighting 要素の 'surfaceScale' 属性を設定します。 |
| [WithFeDistantLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfedistantlight/)(*Action&lt;SVGFEDistantLightElementBuilder&gt;*) |  |
| [WithFePointLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfepointlight/)(*Action&lt;SVGFEPointLightElementBuilder&gt;*) |  |
| [WithFeSpotLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfespotlight/)(*Action&lt;SVGFESpotLightElementBuilder&gt;*) |  |

### 参照

* class [SVGFEBaseLightingElementBuilder&lt;TElement,TBuilder&gt;](../svgfebaselightingelementbuilder-2/)
* class [SVGFEDiffuseLightingElement](../../aspose.svg.filters/svgfediffuselightingelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
