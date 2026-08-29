---
title: "SVGBuilderExtensions.RepeatDur"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions RepeatDur 메서드. 애니메이션이 반복될 전체 기간을 지정하는 repeatDur 속성을 설정합니다."
type: docs
weight: 1960
url: /ko/net/aspose.svg.builder/svgbuilderextensions/repeatdur/
---
## RepeatDur<TBuilder>(*this TBuilder, TimeSpan*) {#repeatdur_1}

애니메이션이 반복될 전체 지속 시간을 지정하는 'repeatDur' 속성을 설정합니다.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 지속 시간 | 애니메이션을 반복하는 전체 기간입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatDur<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatdur}

미리 정의된 열거형을 사용하여 애니메이션의 무한 전체 지속 시간을 지정하는 'repeatDur' 속성을 설정합니다.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 애니메이션을 반복하기 위한 미리 정의된 무한 전체 기간입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
