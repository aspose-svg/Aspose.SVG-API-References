---
title: "SVGBuilderExtensions.RepeatCount"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions RepeatCount metodu. Animasyonun kaç kez tekrarlanacağını tanımlayan repeatCount özniteliğini ayarlar"
type: docs
weight: 1950
url: /tr/net/aspose.svg.builder/svgbuilderextensions/repeatcount/
---
## RepeatCount<TBuilder>(*this TBuilder, int*) {#repeatcount_1}

'repeatCount' özniteliğini ayarlar, animasyonun kaç kez tekrarlanacağını tanımlar.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, int value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Animasyonun tekrarlanması gereken sayı. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatCount<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatcount}

'repeatCount' özniteliğini ayarlar, önceden tanımlı bir enum kullanarak animasyon için süresiz bir tekrar sayısı tanımlar.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Animasyon için önceden tanımlanmış belirsiz tekrar sayısı. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
