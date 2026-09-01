---
title: "SVGBuilderExtensions.RequiredExtensions"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions RequiredExtensions yöntemi. SVG öğesinde requiredExtensions özniteliğini ayarlar. Bu öznitelik, SVG belge parçasının işlenmesi için hangi uzantıların gerekli olduğunu belirtir"
type: docs
weight: 1970
url: /tr/net/aspose.svg.builder/svgbuilderextensions/requiredextensions/
---
## SVGBuilderExtensions.RequiredExtensions<TBuilder> method

SVG öğesinde 'requiredExtensions' özniteliğini ayarlar. Bu öznitelik, SVG belge parçasının işlenmesi için hangi uzantıların gerekli olduğunu belirtir.

```csharp
public static TBuilder RequiredExtensions<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IConditionalProcessingAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Özniteliğin ayarlandığı SVG öğesi oluşturucu. |
| value | Gerekli uzantıları temsil eden bir dize değeri. |

### Dönüş Değeri

Yöntem zincirlemesi için orijinal SVG öğesi oluşturucu.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../../iconditionalprocessingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
