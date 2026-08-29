---
title: "SVGScriptElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGScriptElementBuilder 클래스. SVG 스크립트 요소를 구성하기 위한 빌더 클래스. 스크립트 요소는 SVG 문서 내에서 실행 가능한 스크립트를 삽입하거나 참조하는 데 사용됩니다. 이 클래스는 type, source, cross-origin 설정과 같은 스크립트 요소 전용 다양한 속성을 설정하는 메서드를 제공합니다."
type: docs
weight: 1600
url: /ko/net/aspose.svg.builder/svgscriptelementbuilder/
---
## SVGScriptElementBuilder class

SVG 'script' 요소를 구성하기 위한 Builder 클래스이며, 'script' 요소는 SVG 문서에 실행 가능한 스크립트를 삽입하거나 참조하는 데 사용됩니다. 이 클래스는 type, source, cross-origin 설정과 같은 'script' 요소에 특화된 다양한 속성을 설정하는 메서드를 제공합니다.

```csharp
public class SVGScriptElementBuilder : SVGElementBuilder<SVGScriptElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGScriptElementBuilder](svgscriptelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGScriptElement](../../aspose.svg/svgscriptelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Crossorigin](../../aspose.svg.builder/svgscriptelementbuilder/crossorigin/)(*string*) | SVG 'script' 요소의 'crossorigin' 속성을 설정하여 외부 스크립트의 CORS 설정을 지정합니다. |
| [Href](../../aspose.svg.builder/svgscriptelementbuilder/href/)(*string*) | SVG 'script' 요소의 'href' 속성을 설정하여 외부 스크립트 파일의 URL을 지정합니다. |
| [Type](../../aspose.svg.builder/svgscriptelementbuilder/type/)(*string*) | SVG 'script' 요소의 'type' 속성을 설정하여 스크립팅 언어 유형을 지정합니다 (예: "text/javascript"). |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGScriptElement](../../aspose.svg/svgscriptelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
