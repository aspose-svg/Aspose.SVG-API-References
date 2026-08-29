---
title: "SVGBuilderExtensions.Max"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Max 메서드. 애니메이션의 최대 지속 시간을 지정하는 max 속성을 설정합니다."
type: docs
weight: 1160
url: /ko/net/aspose.svg.builder/svgbuilderextensions/max/
---
## Max<TBuilder>(*this TBuilder, TimeSpan*) {#max_1}

'max' 속성을 설정하고, 애니메이션의 최대 지속 시간을 지정합니다.

```csharp
public static TBuilder Max<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 지속 시간 | 애니메이션의 최대 지속 시간입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Max<TBuilder>(*this TBuilder, [Media](../../media/)*) {#max}

'max' 속성을 설정하고, 애니메이션에 대한 미리 정의된 최대 지속 시간 조건을 지정합니다.

```csharp
public static TBuilder Max<TBuilder>(this TBuilder builder, Media value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 애니메이션에 대한 사전 정의된 최대 지속 시간 조건입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [Media](../../media/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
