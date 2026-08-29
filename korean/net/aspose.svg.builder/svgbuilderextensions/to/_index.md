---
title: "SVGBuilderExtensions.To"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions To 메서드. 지정된 길이 유형으로 애니메이션의 종료 값을 정의하는 to 속성을 설정합니다."
type: docs
weight: 2250
url: /ko/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

'to' 속성을 설정하고, 지정된 길이 유형으로 애니메이션의 종료 값을 정의합니다.

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 애니메이션의 종료 값입니다. |
| type | 'to' 값의 길이 유형입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
