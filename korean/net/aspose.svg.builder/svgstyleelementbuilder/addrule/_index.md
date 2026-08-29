---
title: "SVGStyleElementBuilder.AddRule"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGStyleElementBuilder AddRule 메서드. 스타일 요소에 CSS 규칙을 추가합니다."
type: docs
weight: 30
url: /ko/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

스타일 요소에 CSS 규칙을 추가합니다.

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| selector | String | 규칙에 대한 CSS 선택자. |
| 규칙 | String | CSS 규칙을 문자열로 나타낸 것입니다. |

### 반환 값

체이닝을 위한 SVGStyleElementBuilder 인스턴스입니다.

### 또 보기

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

RuleBuilder를 사용하여 스타일 요소에 CSS 규칙을 추가합니다.

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| selector | String | 규칙에 대한 CSS 선택자. |
| configureRule | Action`1 | RuleBuilder를 사용하여 규칙을 구성하는 대리자. |

### 반환 값

체이닝을 위한 SVGStyleElementBuilder 인스턴스입니다.

### 또 보기

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
