---
title: "SVGBuilderExtensions.Transform"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions Transform yöntemi. Bir SVG öğesi için transform özniteliğini ayarlar"
type: docs
weight: 2260
url: /tr/net/aspose.svg.builder/svgbuilderextensions/transform/
---
## SVGBuilderExtensions.Transform<TBuilder> method

Bir SVG öğesi için 'transform' özniteliğini ayarlar.

```csharp
public static TBuilder Transform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, ITransformAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | SVG dönüşümünü yapılandırmak için bir işlev. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransformAttributeSetter](../../itransformattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
