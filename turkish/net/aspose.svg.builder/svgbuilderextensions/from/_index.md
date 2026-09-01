---
title: "SVGBuilderExtensions.From"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions From yöntemi. Belirli bir uzunluk türüyle animasyonun başlangıç değerini tanımlayan from özniteliğini ayarlar"
type: docs
weight: 960
url: /tr/net/aspose.svg.builder/svgbuilderextensions/from/
---
## SVGBuilderExtensions.From<TBuilder> method

'from' özniteliğini ayarlar, animasyonun başlangıç değerini belirtilen bir uzunluk türüyle tanımlar.

```csharp
public static TBuilder From<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Animasyonun başlangıç değeri. |
| tip | 'from' değeri için uzunluk türü. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
