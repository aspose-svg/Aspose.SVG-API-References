---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGFEColorMatrixElementBuilder TypeAndValues 메서드. 색상 매트릭스 연산 및 그 매개변수를 지정하는 feColorMatrix 요소의 type 및 values 속성을 설정합니다."
type: docs
weight: 30
url: /ko/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

feColorMatrix 요소의 'type' 및 'values' 속성을 설정하여 색상 매트릭스 연산과 해당 매개변수를 지정합니다.

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | ColorMatrixOperation | 색상 매트릭스 연산 유형을 나타내는 ColorMatrixOperation 열거형 값. |
| values | Double[] | 색상 매트릭스 연산에 대한 매개변수. |

### 반환 값

현재 빌더 인스턴스.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 제공된 값이 지정된 유형의 요구 사항과 일치하지 않을 때 발생합니다. |
| NotSupportedException | 지원되지 않는 매트릭스 연산 유형이 제공될 때 발생합니다. |

### 또 보기

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
