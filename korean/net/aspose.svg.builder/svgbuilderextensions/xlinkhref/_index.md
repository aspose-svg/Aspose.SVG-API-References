---
title: "SVGBuilderExtensions.XlinkHref"
second_title: "Aspose.SVG for .NET API 참조"
description: "SVGBuilderExtensions XlinkHref 메서드. SVG 요소에 대한 xlinkhref 속성을 설정합니다. 이 속성은 리소스에 대한 참조를 링크로 정의하는 데 사용됩니다."
type: docs
weight: 2370
url: /ko/net/aspose.svg.builder/svgbuilderextensions/xlinkhref/
---
## SVGBuilderExtensions.XlinkHref<TBuilder> method

SVG 요소에 'xlink:href' 속성을 설정합니다. 이 속성은 리소스에 대한 링크 참조를 정의하는 데 사용됩니다.

```csharp
public static TBuilder XlinkHref<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IXLinkAttributeSetter
```

| 매개변수 | 설명 |
| --- | --- |
| TBuilder | SVG 요소 빌더의 유형입니다. |
| 빌더 | 빌더 인스턴스입니다. |
| 값 | 링크할 리소스의 URI입니다. |

### 반환 값

체이닝을 위한 빌더 인스턴스입니다.

### 또 보기

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IXLinkAttributeSetter](../../ixlinkattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
