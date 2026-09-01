---
title: "SVGBuilderExtensions.Dx"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions Dx yöntemi. Metindeki her karakterin yatay konumunu ayarlamak için dx özniteliğini belirler"
type: docs
weight: 770
url: /tr/net/aspose.svg.builder/svgbuilderextensions/dx/
---
## Dx<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#dx}

'dx' özniteliğini ayarlar, metindeki her karakterin yatay konumunu ayarlamak için.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| tip | Değerler için uzunluk birimi türü. |
| values | Her karakter için yatay ayarlama değerleri. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

## Açıklamalar

Bu yöntem, metindeki karakterlerin yatay aralığı üzerinde hassas kontrol sağlar.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dx<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dx_1}

Metin içeriği için tek bir yatay ayarlama değeri ayarlar.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Yatay ayarlama değeri. |
| tip | Değer için uzunluk birimi türü. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

## Açıklamalar

Bu yöntem, 'dx' özniteliğini tek bir değerle ayarlar ve metin içeriğinin yatay konumunu düzenler.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
