---
title: "SVGFESpecularLightingElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGFESpecularLightingElementBuilder 클래스. 이미지에 반사 조명 효과를 적용하는 SVG feSpecularLighting 요소를 생성하기 위한 빌더 클래스"
type: docs
weight: 1400
url: /ko/net/aspose.svg.builder/svgfespecularlightingelementbuilder/
---
## SVGFESpecularLightingElementBuilder class

SVG 'feSpecularLighting' 요소를 생성하기 위한 Builder 클래스이며, 이미지에 반사 조명 효과를 적용합니다.

```csharp
public class SVGFESpecularLightingElementBuilder : 
    SVGFEBaseLightingElementBuilder<SVGFESpecularLightingElement, SVGFESpecularLightingElementBuilder>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGFESpecularLightingElementBuilder](svgfespecularlightingelementbuilder/)() | 기본 생성자입니다. |

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
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFESpecularLightingElement](../../aspose.svg.filters/svgfespecularlightingelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [KernelUnitLength](../../aspose.svg.builder/svgfespecularlightingelementbuilder/kernelunitlength/)(*double, double?*) | 'kernelUnitLength' 속성을 설정하여 컨볼루션 커널 단위 길이를 정의합니다. |
| [SpecularConstant](../../aspose.svg.builder/svgfespecularlightingelementbuilder/specularconstant/)(*double*) | 'specularConstant' 속성을 설정하여 반사 상수 값을 나타냅니다. |
| [SpecularExponent](../../aspose.svg.builder/svgfespecularlightingelementbuilder/specularexponent/)(*double*) | 'specularExponent' 속성을 설정하여, 반사 하이라이트의 초점을 제어합니다. |
| [SurfaceScale](../../aspose.svg.builder/svgfespecularlightingelementbuilder/surfacescale/)(*double*) | feSpecularLighting 요소의 'surfaceScale' 속성을 설정하여 조명 계산을 위한 표면 높이를 정의합니다. |
| [WithFeDistantLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfedistantlight/)(*Action&lt;SVGFEDistantLightElementBuilder&gt;*) |  |
| [WithFePointLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfepointlight/)(*Action&lt;SVGFEPointLightElementBuilder&gt;*) |  |
| [WithFeSpotLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfespotlight/)(*Action&lt;SVGFESpotLightElementBuilder&gt;*) |  |

### 또 보기

* class [SVGFEBaseLightingElementBuilder&lt;TElement,TBuilder&gt;](../svgfebaselightingelementbuilder-2/)
* class [SVGFESpecularLightingElement](../../aspose.svg.filters/svgfespecularlightingelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
