---
title: "SVGBuilderExtensions.OnSeeking"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions OnSeeking metodu. Medyada bir arama (seek) işlemi başlatıldığında olayları işlemek için onseeking olay özniteliğini ayarlar"
type: docs
weight: 1750
url: /tr/net/aspose.svg.builder/svgbuilderextensions/onseeking/
---
## SVGBuilderExtensions.OnSeeking<TBuilder> method

Medya üzerinde bir arama işlemi başlatıldığında oluşan olayları işlemek üzere 'onseeking' olay özniteliğini ayarlar.

```csharp
public static TBuilder OnSeeking<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Arama (seek) işlemi başlatıldığında çalıştırılacak JavaScript işlevi veya betiği. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
