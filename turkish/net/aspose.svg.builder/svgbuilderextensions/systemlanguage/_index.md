---
title: "SVGBuilderExtensions.SystemLanguage"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions SystemLanguage yöntemi. SVG öğesinde systemLanguage özniteliğini ayarlar. Bu öznitelik, SVG belge parçasının hedeflendiği dil tercihlerini belirtir."
type: docs
weight: 2170
url: /tr/net/aspose.svg.builder/svgbuilderextensions/systemlanguage/
---
## SVGBuilderExtensions.SystemLanguage<TBuilder> method

SVG öğesi üzerinde 'systemLanguage' özniteliğini ayarlar. Bu öznitelik, SVG belge parçasının hedeflendiği dil tercihlerini belirtir.

```csharp
public static TBuilder SystemLanguage<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IConditionalProcessingAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Özniteliğin ayarlandığı SVG öğesi oluşturucu. |
| value | Dil tercihlerini temsil eden bir string değer, genellikle dil etiketleri biçiminde. |

### Dönüş Değeri

Yöntem zincirlemesi için orijinal SVG öğesi oluşturucu.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../../iconditionalprocessingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
