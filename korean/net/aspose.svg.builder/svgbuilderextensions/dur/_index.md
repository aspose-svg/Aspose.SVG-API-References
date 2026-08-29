---
title: "SVGBuilderExtensions.Dur"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Dur 메서드. 애니메이션의 지속 시간을 지정하는 dur 속성을 설정합니다."
type: docs
weight: 760
url: /ko/net/aspose.svg.builder/svgbuilderextensions/dur/
---
## Dur<TBuilder>(*this TBuilder, TimeSpan*) {#dur_1}

'dur' 속성을 설정하고, 애니메이션의 지속 시간을 지정합니다.

```csharp
public static TBuilder Dur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 지속 시간 | 애니메이션의 지속 시간입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dur<TBuilder>(*this TBuilder, [Dur](../../dur/)*) {#dur}

'dur' 속성을 설정하고, 애니메이션의 미리 정의된 지속 시간 유형을 지정합니다.

```csharp
public static TBuilder Dur<TBuilder>(this TBuilder builder, Dur value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 애니메이션에 대한 미리 정의된 지속 시간 유형입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [Dur](../../dur/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
