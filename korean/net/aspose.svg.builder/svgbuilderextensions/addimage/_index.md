---
title: "SVGBuilderExtensions.AddImage"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions AddImage 메서드. 빌더에 이미지 요소 구성을 추가합니다"
type: docs
weight: 330
url: /ko/net/aspose.svg.builder/svgbuilderextensions/addimage/
---
## AddImage<TBuilder>(*this TBuilder, Action&lt;SVGImageElementBuilder&gt;*) {#addimage}

빌더에 'image' 요소 구성을 추가합니다.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, 
    Action<SVGImageElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 'image' 요소에 대한 구성 작업. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddImage<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, string, Action&lt;SVGImageElementBuilder&gt;*) {#addimage_1}

SVG 빌더에 'image' 요소를 추가하여 외부 이미지를 SVG 문서에 삽입합니다.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, string id = null, 
    Action<SVGImageElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | 유창한 API 사용을 가능하게 하는 SVG 요소 빌더의 유형입니다. |
| 빌더 | 'image' 요소가 추가될 SVG 빌더 인스턴스. |
| href | 외부 이미지에 대한 URL 또는 참조. 선택 매개변수. |
| x | 이미지가 배치되는 x 좌표. double 또는 LengthType이 포함된 ValueTuple일 수 있음. 선택 매개변수. |
| y | 이미지가 배치되는 y 좌표. double 또는 LengthType이 포함된 ValueTuple일 수 있음. 선택 매개변수. |
| width | 이미지의 너비. double 또는 LengthType이 포함된 ValueTuple일 수 있음. 선택 매개변수. |
| height | 이미지의 높이. double 또는 LengthType이 포함된 ValueTuple일 수 있음. 선택 매개변수. |
| id | 이미지 요소의 고유 식별자. 선택 매개변수. |
| extend | SVGImageElementBuilder를 추가로 구성하기 위한 선택 작업. |

### 반환 값

빌더 인스턴스이며, 메서드 체이닝을 허용합니다.

### 또 보기

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
