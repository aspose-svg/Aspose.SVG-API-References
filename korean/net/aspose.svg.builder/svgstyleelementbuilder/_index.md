---
title: "SVGStyleElementBuilder 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGStyleElementBuilder 클래스. SVG 스타일 요소를 구성하기 위한 빌더 클래스입니다. 이 클래스는 CSS 규칙을 사용하여 SVG 스타일 요소를 생성하고 구성하는 작업을 용이하게 합니다."
type: docs
weight: 1630
url: /ko/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

SVG 'style' 요소를 구성하기 위한 Builder 클래스이며, 이 클래스는 CSS 규칙을 가진 SVG 스타일 요소의 생성 및 구성을 용이하게 합니다.

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | 스타일 내용에 주석을 추가합니다. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | RuleBuilder를 사용하여 스타일 요소에 CSS 규칙을 추가합니다. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | 스타일 요소에 CSS 규칙을 추가합니다. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | 누적된 CSS 규칙으로 SVG 스타일 요소를 구축하고 지정된 문서에 추가합니다. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | SVG 'style' 요소의 'media' 속성을 설정합니다. 이 속성은 스타일이 적용될 미디어를 지정하여 미디어 유형에 따라 스타일을 조건부로 적용할 수 있게 합니다. |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | SVG 'style' 요소의 'title' 속성을 설정합니다. 이 속성은 스타일 요소에 대한 안내 제목을 제공하며, 접근성 및 툴팁 텍스트에 유용할 수 있습니다. |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | SVG 'style' 요소의 'type' 속성을 설정합니다. 이 속성은 요소 내용의 스타일시트 언어를 지정합니다. |

### 또 보기

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
