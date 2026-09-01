---
title: "SVGBuilderExtensions.FontSize"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions FontSize yöntemi. Sayısal bir değer ve belirli bir uzunluk türü kullanarak bir SVG öğesi için font-size özniteliğini ayarlar"
type: docs
weight: 890
url: /tr/net/aspose.svg.builder/svgbuilderextensions/fontsize/
---
## FontSize<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontsize_1}

Bir SVG öğesi için 'font-size' özniteliğini sayısal bir değer ve belirli bir uzunluk türü kullanarak ayarlar.

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| value | Ayarlanacak yazı tipi boyutu değeri. |
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

## FontSize<TBuilder>(*this TBuilder, [FontSize](../../fontsize/)*) {#fontsize}

Önceden tanımlı bir font boyutu değeri kullanarak bir SVG öğesi için 'font-size' özniteliğini ayarlar.

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, FontSize value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| value | Ayarlanacak önceden tanımlı yazı tipi boyutu değeri. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [FontSize](../../fontsize/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
