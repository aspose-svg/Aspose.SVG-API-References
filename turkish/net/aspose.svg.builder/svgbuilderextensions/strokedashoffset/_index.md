---
title: "SVGBuilderExtensions.StrokeDashoffset"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions StrokeDashoffset yöntemi. SVG öğesi için çizgi çizgi aralığı dizisinin başlangıç ofsetini tanımlayan stroke-dashoffset özniteliğini ayarlar"
type: docs
weight: 2100
url: /tr/net/aspose.svg.builder/svgbuilderextensions/strokedashoffset/
---
## SVGBuilderExtensions.StrokeDashoffset<TBuilder> method

SVG öğesi için 'stroke-dashoffset' özniteliğini ayarlar, çizgi dash dizisinin başlangıç ofsetini tanımlar.

```csharp
public static TBuilder StrokeDashoffset<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| value | Çizgi ofset değeri. |
| tip | Ofset değeri için birim türü. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
