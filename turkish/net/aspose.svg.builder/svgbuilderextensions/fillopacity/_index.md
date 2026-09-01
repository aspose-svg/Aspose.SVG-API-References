---
title: "SVGBuilderExtensions.FillOpacity"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions FillOpacity yöntemi. Bir SVG öğesi için fill-opacity özniteliğini ayarlar. Değer 0.0 tam şeffaf ile 1.0 tam opak arasında olmalıdır"
type: docs
weight: 820
url: /tr/net/aspose.svg.builder/svgbuilderextensions/fillopacity/
---
## SVGBuilderExtensions.FillOpacity<TBuilder> method

Bir SVG öğesi için 'fill-opacity' özniteliğini ayarlar. Değer 0.0 (tamamen şeffaf) ile 1.0 (tamamen opak) arasında olmalıdır.

```csharp
public static TBuilder FillOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| opacity | Ayarlanacak opaklık değeri. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | Opaklık geçerli aralıkta değilse fırlatılır. |

### Ayrıca Bakınız

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
