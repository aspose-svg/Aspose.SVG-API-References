---
title: "SVGFEDiffuseLightingElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGFEDiffuseLightingElementBuilder 클래스. SVG 필터에서 확산 조명 효과를 적용하기 위해 사용되는 SVG feDiffuseLighting 요소를 생성하는 빌더 클래스"
type: docs
weight: 1240
url: /ko/net/aspose.svg.builder/svgfediffuselightingelementbuilder/
---
## SVGFEDiffuseLightingElementBuilder class

확산 조명 효과를 적용하기 위해 SVG 필터에서 사용되는 SVG 'feDiffuseLighting' 요소를 생성하기 위한 Builder 클래스입니다.

```csharp
public class SVGFEDiffuseLightingElementBuilder : 
    SVGFEBaseLightingElementBuilder<SVGFEDiffuseLightingElement, SVGFEDiffuseLightingElementBuilder>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGFEDiffuseLightingElementBuilder](svgfediffuselightingelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) |  |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEDiffuseLightingElement](../../aspose.svg.filters/svgfediffuselightingelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [DiffuseConstant](../../aspose.svg.builder/svgfediffuselightingelementbuilder/diffuseconstant/)(*double*) | feDiffuseLighting 요소의 'diffuseConstant' 속성을 설정합니다. |
| [KernelUnitLength](../../aspose.svg.builder/svgfediffuselightingelementbuilder/kernelunitlength/)(*double, double?*) | feDiffuseLighting 요소의 'kernelUnitLength' 속성을 설정합니다. |
| [SurfaceScale](../../aspose.svg.builder/svgfediffuselightingelementbuilder/surfacescale/)(*double*) | feDiffuseLighting 요소의 'surfaceScale' 속성을 설정합니다. |
| [WithFeDistantLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfedistantlight/)(*Action&lt;SVGFEDistantLightElementBuilder&gt;*) |  |
| [WithFePointLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfepointlight/)(*Action&lt;SVGFEPointLightElementBuilder&gt;*) |  |
| [WithFeSpotLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfespotlight/)(*Action&lt;SVGFESpotLightElementBuilder&gt;*) |  |

### 또 보기

* class [SVGFEBaseLightingElementBuilder&lt;TElement,TBuilder&gt;](../svgfebaselightingelementbuilder-2/)
* class [SVGFEDiffuseLightingElement](../../aspose.svg.filters/svgfediffuselightingelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
