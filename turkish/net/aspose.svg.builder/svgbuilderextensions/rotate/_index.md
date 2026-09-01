---
title: "SVGBuilderExtensions.Rotate"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions Rotate yöntemi. Metin içeriğinin bireysel karakterleri veya bölümleri için dönüş açılarını ayarlar."
type: docs
weight: 2000
url: /tr/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

Metin içeriğinin bireysel karakterleri veya bölümleri için dönüş açılarını ayarlar.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| values | Derece cinsinden dönüş açıları dizisi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

## Açıklamalar

Bu yöntem, her karakter veya metin segmentinin bireysel olarak döndürülmesine izin vererek 'rotate' özniteliğini birden fazla değerle ayarlar.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

Tüm metin içeriği için tek bir döndürme açısı ayarlar.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Derece cinsinden dönüş açısı. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

## Açıklamalar

Bu yöntem, tüm metin içeriğine aynı dönüş açısını uygulayarak 'rotate' özniteliğini tek bir değerle ayarlar.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
