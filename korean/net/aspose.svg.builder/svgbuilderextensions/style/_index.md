---
title: "SVGBuilderExtensions.Style"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Style 메서드. 규칙 빌더를 사용하여 CSS 스타일을 정의하고 style 속성을 설정합니다."
type: docs
weight: 2160
url: /ko/net/aspose.svg.builder/svgbuilderextensions/style/
---
## Style<TBuilder>(*this TBuilder, Action&lt;RuleBuilder&gt;*) {#style}

규칙 빌더를 사용하여 CSS 스타일을 정의하고, 'style' 속성을 설정합니다.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, Action<RuleBuilder> configureRule)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| configureRule | CSS 규칙을 구성하기 위한 동작입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [RuleBuilder](../../rulebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Style<TBuilder>(*this TBuilder, string*) {#style_1}

SVG 요소에 대한 인라인 CSS 스타일을 정의하고, 'style' 속성을 설정합니다.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, string rules)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 규칙 | CSS 규칙을 문자열로 나타낸 것입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
