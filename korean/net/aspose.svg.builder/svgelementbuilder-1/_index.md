---
title: "SVGElementBuilderT 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.SVGElementBuilder1T 클래스. 유형 T의 SVG 요소를 구축하기 위한 기본 클래스를 나타냅니다."
type: docs
weight: 1160
url: /ko/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

*T* 유형의 SVG 요소를 구축하기 위한 기본 클래스를 나타냅니다.

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| 매개변수 | 설명 |
| --- | --- |
| T | 이 빌더가 생성할 책임이 있는 SVG 요소의 유형입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | SVG 요소에 적용될 구성 목록을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | SVG 요소에 속성 구성을 추가합니다. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | SVG 요소를 구축하고 모든 구성을 적용합니다. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | 기존 SVG 요소에 구성을 적용합니다. |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | SVG 요소를 일반 SVGElement로 구축합니다. |

### 또 보기

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
