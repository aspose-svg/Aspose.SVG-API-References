---
title: "SVGBuilderExtensions.Mask"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Mask 메서드. 사용자 정의 마스크 구성을 사용하여 SVG 요소의 mask 속성을 설정합니다."
type: docs
weight: 1150
url: /ko/net/aspose.svg.builder/svgbuilderextensions/mask/
---
## SVGBuilderExtensions.Mask<TBuilder> method

사용자 정의 마스크 구성을 사용하여 SVG 요소에 'mask' 속성을 설정합니다.

```csharp
public static TBuilder Mask<TBuilder>(this TBuilder builder, Action<MaskBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 구성 | 마스크를 구성하기 위한 대리자입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* class [MaskBuilder](../../maskbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
