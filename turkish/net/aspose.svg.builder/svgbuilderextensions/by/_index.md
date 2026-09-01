---
title: "SVGBuilderExtensions.By"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions By yöntemi. Belirtilen uzunluk türüyle animasyon için göreli ofset değerini tanımlayan by özniteliğini ayarlar"
type: docs
weight: 620
url: /tr/net/aspose.svg.builder/svgbuilderextensions/by/
---
## SVGBuilderExtensions.By<TBuilder> method

'by' özniteliğini ayarlar; belirtilen uzunluk türüyle animasyon için göreli ofset değerini tanımlar.

```csharp
public static TBuilder By<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Animasyon için göreli ofset değeri. |
| tip | 'by' değeri için uzunluk türü. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
