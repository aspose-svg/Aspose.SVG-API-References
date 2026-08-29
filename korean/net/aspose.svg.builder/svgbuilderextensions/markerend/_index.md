---
title: "SVGBuilderExtensions.MarkerEnd"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions MarkerEnd 메서드. 경로 끝에 마커를 지정하는 SVG 요소의 marker-end 속성을 설정합니다."
type: docs
weight: 1120
url: /ko/net/aspose.svg.builder/svgbuilderextensions/markerend/
---
## MarkerEnd<TBuilder>(*this TBuilder, string*) {#markerend_1}

SVG 요소에 'marker-end' 속성을 설정하고, 경로 끝에 마커를 지정합니다.

```csharp
public static TBuilder MarkerEnd<TBuilder>(this TBuilder builder, string markerId)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| markerId | 사용할 마커의 ID입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## MarkerEnd<TBuilder>(*this TBuilder, [MarkerPos](../../markerpos/)*) {#markerend}

미리 정의된 마커 위치를 사용하여 SVG 요소에 'marker-end' 속성을 설정합니다.

```csharp
public static TBuilder MarkerEnd<TBuilder>(this TBuilder builder, MarkerPos value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | 설정할 마커 위치 값입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [MarkerPos](../../markerpos/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
