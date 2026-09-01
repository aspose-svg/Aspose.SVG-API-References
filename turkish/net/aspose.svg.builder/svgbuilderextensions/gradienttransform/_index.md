---
title: "SVGBuilderExtensions.GradientTransform"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions GradientTransform metodu. Bir gradient öğesi için gradientTransform özniteliğini ayarlar"
type: docs
weight: 980
url: /tr/net/aspose.svg.builder/svgbuilderextensions/gradienttransform/
---
## SVGBuilderExtensions.GradientTransform<TBuilder> method

Bir gradient öğesi için 'gradientTransform' özniteliğini ayarlar.

```csharp
public static TBuilder GradientTransform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Öznitelik uygulanacak SVG öğesi oluşturucu. |
| yapılandır | SVG dönüşüm oluşturucusunu yapılandırmak için bir işlev. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
