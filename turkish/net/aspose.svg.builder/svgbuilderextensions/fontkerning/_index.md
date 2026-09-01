---
title: "SVGBuilderExtensions.FontKerning"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions FontKerning metodu. Bir SVG öğesi için font-kerning özniteliğini sayısal bir değer ve belirli bir uzunluk türü kullanarak ayarlar."
type: docs
weight: 880
url: /tr/net/aspose.svg.builder/svgbuilderextensions/fontkerning/
---
## FontKerning<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontkerning_1}

Sayısal bir değer ve belirli bir uzunluk türü kullanarak bir SVG öğesi için 'font-kerning' özniteliğini ayarlar.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| value | Ayarlanacak font kerning değeri. |
| tip | Uzunluk türü (ör. px, em). |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FontKerning<TBuilder>(*this TBuilder, [Kerning](../../kerning/)*) {#fontkerning}

Önceden tanımlı bir kerning değeri kullanarak bir SVG öğesi için 'font-kerning' özniteliğini ayarlar.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, Kerning value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| value | Ayarlanacak önceden tanımlı kerning değeri. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [Kerning](../../kerning/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
