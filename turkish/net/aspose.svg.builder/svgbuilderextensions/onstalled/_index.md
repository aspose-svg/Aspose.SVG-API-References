---
title: "SVGBuilderExtensions.OnStalled"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions OnStalled yöntemi. Medya veri aktarımı beklenmedik şekilde durduğunda olayları işlemek için onstalled olay özniteliğini ayarlar"
type: docs
weight: 1780
url: /tr/net/aspose.svg.builder/svgbuilderextensions/onstalled/
---
## SVGBuilderExtensions.OnStalled<TBuilder> method

Medya veri aktarımı beklenmedik bir şekilde durduğunda oluşan olayları işlemek üzere 'onstalled' olay özniteliğini ayarlar.

```csharp
public static TBuilder OnStalled<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Medya veri aktarımı durduğunda çalıştırılacak JavaScript işlevi veya betiği. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
