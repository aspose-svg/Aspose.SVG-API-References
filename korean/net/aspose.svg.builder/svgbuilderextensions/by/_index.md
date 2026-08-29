---
title: "SVGBuilderExtensions.By"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions By 메서드. 지정된 길이 유형으로 애니메이션의 상대적 오프셋 값을 정의하는 by 속성을 설정합니다."
type: docs
weight: 620
url: /ko/net/aspose.svg.builder/svgbuilderextensions/by/
---
## SVGBuilderExtensions.By<TBuilder> method

'by' 속성을 설정하고, 지정된 길이 유형으로 애니메이션의 상대 오프셋 값을 정의합니다.

```csharp
public static TBuilder By<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | SVG 요소 빌더. |
| 값 | 애니메이션의 상대적 오프셋 값입니다. |
| type | 'by' 값의 길이 유형입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
