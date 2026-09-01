---
title: "SVGBuilderExtensions.Points"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions Points yöntemi. Bir SVG öğesi için çift sayı dizisi kullanarak points özniteliğini ayarlar."
type: docs
weight: 1910
url: /tr/net/aspose.svg.builder/svgbuilderextensions/points/
---
## Points<TBuilder>(*this TBuilder, params double[]*) {#points}

Bir SVG öğesi için 'points' özniteliğini, çift sayı dizisi kullanarak ayarlar.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params double[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| points | Noktaları temsil eden çift sayı dizisi (çift sayı olmalıdır). |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | Tek sayıdaki noktalar sağlanırsa fırlatılır. |

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Points<TBuilder>(*this TBuilder, params PointF[]*) {#points_1}

Bir SVG öğesi için 'points' özniteliğini, PointF nesneleri dizisi kullanarak ayarlar.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params PointF[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| points | Noktaları temsil eden PointF nesnelerinin bir dizisi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
