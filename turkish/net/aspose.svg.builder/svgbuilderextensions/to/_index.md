---
title: "SVGBuilderExtensions.To"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions To yöntemi. Belirtilen bir uzunluk türüyle animasyonun bitiş değerini tanımlayan to özniteliğini ayarlar."
type: docs
weight: 2250
url: /tr/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

'to' özniteliğini ayarlar, belirtilen uzunluk türüyle animasyonun bitiş değerini tanımlar.

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Animasyonun bitiş değeri. |
| tip | 'to' değeri için uzunluk türü. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
