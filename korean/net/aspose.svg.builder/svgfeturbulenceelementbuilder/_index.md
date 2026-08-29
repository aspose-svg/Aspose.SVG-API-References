---
title: "SVGFETurbulenceElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGFETurbulenceElementBuilder 클래스. Perlin 난류 함수를 사용하여 이미지를 생성하는 SVG feTurbulence 요소를 만들기 위한 빌더 클래스"
type: docs
weight: 1430
url: /ko/net/aspose.svg.builder/svgfeturbulenceelementbuilder/
---
## SVGFETurbulenceElementBuilder class

SVG 'feTurbulence' 요소를 생성하기 위한 Builder 클래스이며, Perlin 난류 함수를 사용하여 이미지를 생성합니다.

```csharp
public class SVGFETurbulenceElementBuilder : SVGElementBuilder<SVGFETurbulenceElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGFETurbulenceElementBuilder](svgfeturbulenceelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfeturbulenceelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feTurbulence 요소에 스크립트 구성을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| [BaseFrequency](../../aspose.svg.builder/svgfeturbulenceelementbuilder/basefrequency/)(*double, double?*) | 난류 함수의 기본 주파수를 설정합니다. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFETurbulenceElement](../../aspose.svg.filters/svgfeturbulenceelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [NumOctaves](../../aspose.svg.builder/svgfeturbulenceelementbuilder/numoctaves/)(*int*) | 난류 함수의 옥타브 수를 설정합니다. |
| [Seed](../../aspose.svg.builder/svgfeturbulenceelementbuilder/seed/)(*double*) | 난류 함수에서 사용되는 난수 생성기의 시드를 설정합니다. |
| [StitchTiles](../../aspose.svg.builder/svgfeturbulenceelementbuilder/stitchtiles/)(*[StitchTiles](../stitchtiles/)*) | 난류 함수의 스티치 타일 옵션을 설정합니다. |
| [Type](../../aspose.svg.builder/svgfeturbulenceelementbuilder/type/)(*[TurbulenceType](../turbulencetype/)*) | 난류 유형(프랙탈 노이즈 또는 난류)을 설정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFETurbulenceElement](../../aspose.svg.filters/svgfeturbulenceelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
