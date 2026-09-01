---
title: "SVGBuilderExtensions.OnPlaying"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions OnPlaying yöntemi. Medya duraklatıldıktan veya tamponlama için durdurulduktan sonra aktif olarak oynatıldığında olayları işlemek için onplaying olay özniteliğini ayarlar"
type: docs
weight: 1670
url: /tr/net/aspose.svg.builder/svgbuilderextensions/onplaying/
---
## SVGBuilderExtensions.OnPlaying<TBuilder> method

Medya tamponlama için duraklatıldıktan veya durdurulduktan sonra aktif olarak çalarken oluşan olayları işlemek üzere 'onplaying' olay özniteliğini ayarlar.

```csharp
public static TBuilder OnPlaying<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Medya aktif olarak oynatıldığında yürütülecek JavaScript fonksiyonu veya betiği. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
