---
title: "SVGBuilderExtensions.X"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions X yöntemi. Bir SVG öğesi için x özniteliğini ayarlar."
type: docs
weight: 2360
url: /tr/net/aspose.svg.builder/svgbuilderextensions/x/
---
## X<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#x_1}

Bir SVG öğesi için 'x' özniteliğini ayarlar.

```csharp
public static TBuilder X<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IXAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| value | 'x' özniteliği için değer. |
| tip | Uzunluk ölçüm tipi (varsayılan piksel). |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IXAttributeSetter](../../ixattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## X<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#x}

Metin içeriğini x ekseni boyunca konumlandırmak için 'x' özniteliğini ayarlar.

```csharp
public static TBuilder X<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| tip | Değerler için uzunluk birimi türü. |
| values | x ekseni konum değerleri. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

## Açıklamalar

Bu yöntem, metin öğesinin yatay konum(ları) belirleyen 'x' özniteliğini ayarlar.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
