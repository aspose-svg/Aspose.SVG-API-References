---
title: "SVGBuilderExtensions.BaselineShift"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions BaselineShift yöntemi. Önceden tanımlı bir değer kullanarak bir SVG öğesi için baseline-shift özniteliğini ayarlar."
type: docs
weight: 600
url: /tr/net/aspose.svg.builder/svgbuilderextensions/baselineshift/
---
## BaselineShift<TBuilder>(*this TBuilder, [BaseLineShift](../../baselineshift/)*) {#baselineshift}

Önceden tanımlı bir değer kullanarak bir SVG öğesi için 'baseline-shift' özniteliğini ayarlar.

```csharp
public static TBuilder BaselineShift<TBuilder>(this TBuilder builder, BaseLineShift value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| value | Ayarlanacak baseline shift değeri. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [BaseLineShift](../../baselineshift/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## BaselineShift<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#baselineshift_1}

Sayısal bir değer kullanarak bir SVG öğesi için 'baseline-shift' özniteliğini ayarlar.

```csharp
public static TBuilder BaselineShift<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| value | Baseline shift için sayısal değer. |
| tip | Uzunluk biriminin türü. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
