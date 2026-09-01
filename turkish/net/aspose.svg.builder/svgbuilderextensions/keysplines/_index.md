---
title: "SVGBuilderExtensions.KeySplines"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions KeySplines yöntemi. Animasyonun temposu için kontrol noktalarını belirten keySplines özniteliğini ayarlar."
type: docs
weight: 1060
url: /tr/net/aspose.svg.builder/svgbuilderextensions/keysplines/
---
## SVGBuilderExtensions.KeySplines<TBuilder> method

'keySplines' özniteliğini ayarlar, animasyonun temposu için kontrol noktalarını belirtir.

```csharp
public static TBuilder KeySplines<TBuilder>(this TBuilder builder, 
    Action<AnimationSplineBuilder> buildSplines)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| buildSplines | Spline yapılandırmasını oluşturmak için eylem. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [AnimationSplineBuilder](../../animationsplinebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
