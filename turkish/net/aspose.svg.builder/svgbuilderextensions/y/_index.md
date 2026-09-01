---
title: "SVGBuilderExtensions.Y"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions Y yöntemi. Bir SVG öğesi için y özniteliğini ayarlar"
type: docs
weight: 2400
url: /tr/net/aspose.svg.builder/svgbuilderextensions/y/
---
## Y<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#y_1}

Bir SVG öğesi için 'y' özniteliğini ayarlar.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IYAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| value | 'y' özniteliği için değer. |
| tip | Uzunluk ölçüm tipi (varsayılan piksel). |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IYAttributeSetter](../../iyattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Y<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#y}

Metin içeriğini y ekseni boyunca konumlandırmak için 'y' özniteliğini ayarlar.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| tip | Değerler için uzunluk birimi türü. |
| values | y ekseni konum değerleri. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

## Açıklamalar

Bu yöntem, metin öğesinin dikey konumunu belirleyen 'y' özniteliğini ayarlar.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
