---
title: "SVGBuilderExtensions.StrokeWidth"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions StrokeWidth yöntemi. Bir SVG öğesi için çizgi kalınlığını tanımlayan stroke-width özniteliğini ayarlar"
type: docs
weight: 2150
url: /tr/net/aspose.svg.builder/svgbuilderextensions/strokewidth/
---
## SVGBuilderExtensions.StrokeWidth<TBuilder> method

SVG öğesi için 'stroke-width' özniteliğini ayarlar, çizginin genişliğini tanımlar.

```csharp
public static TBuilder StrokeWidth<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| value | Çizgi kalınlığı değeri. |
| tip | Çizgi kalınlığı için birim türü. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
