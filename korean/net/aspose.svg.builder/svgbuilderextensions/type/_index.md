---
title: "SVGBuilderExtensions.Type"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions Type 메서드. 구성 요소 전송 함수 요소의 type 속성을 설정합니다"
type: docs
weight: 2270
url: /ko/net/aspose.svg.builder/svgbuilderextensions/type/
---
## SVGBuilderExtensions.Type<TBuilder> method

컴포넌트 전송 함수 요소의 'type' 속성을 설정합니다.

```csharp
public static TBuilder Type<TBuilder>(this TBuilder builder, ComponentTransferType type)
    where TBuilder : ISVGElementBuilder, ITransferFunctionAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| type | 구성 요소 전송 함수의 유형 (예: linear, gamma). |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* enum [ComponentTransferType](../../componenttransfertype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransferFunctionAttributeSetter](../../itransferfunctionattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
