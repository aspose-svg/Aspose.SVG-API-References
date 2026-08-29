---
title: "SVGBuilderExtensions.RefY"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions RefY 메서드. SVG 요소의 refY 속성을 설정합니다."
type: docs
weight: 1940
url: /ko/net/aspose.svg.builder/svgbuilderextensions/refy/
---
## RefY<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#refy_1}

SVG 요소의 'refY' 속성을 설정합니다.

```csharp
public static TBuilder RefY<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | 참조 Y 좌표입니다. |
| type | 길이 단위 유형(기본값은 픽셀). |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RefY<TBuilder>(*this TBuilder, [VerticalPosition](../../verticalposition/)*) {#refy}

미리 정의된 수직 위치를 사용하여 SVG 요소의 'refY' 속성을 설정합니다.

```csharp
public static TBuilder RefY<TBuilder>(this TBuilder builder, VerticalPosition value)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | 미리 정의된 수직 위치입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [VerticalPosition](../../verticalposition/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
