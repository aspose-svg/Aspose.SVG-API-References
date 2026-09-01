---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddBuilder yöntemi. Mevcut SVG öğe oluşturucuya mevcut bir SVG öğe oluşturucu ekler. Bu yöntem, önceden tanımlı bir SVG öğe oluşturucuyu mevcut oluşturucuya dahil etmek için kullanılır."
type: docs
weight: 60
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

Mevcut SVG öğe oluşturucuya mevcut bir SVG öğe oluşturucu ekler. Bu yöntem, önceden tanımlanmış bir SVG öğe oluşturucusunu mevcut oluşturucuya dahil etmek için kullanılır.

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| TElementBuilder | Yapılandırılacak SVG öğe oluşturucunun türü. TElementBuilder, ISVGElementBuilder'ı uygulamalıdır. |
| oluşturucu | Diğer öğe oluşturucunun eklendiği SVG öğe oluşturucu. |
| elementBuilder | Eklenecek SVG öğe oluşturucu. |

### Dönüş Değeri

Yöntem zincirlemesi için orijinal SVG öğesi oluşturucu.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
