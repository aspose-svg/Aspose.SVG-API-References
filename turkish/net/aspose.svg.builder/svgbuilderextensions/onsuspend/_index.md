---
title: "SVGBuilderExtensions.OnSuspend"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions OnSuspend yöntemi. Medya veri yüklemesi askıya alındığında olayları işlemek için onsuspend olay özniteliğini ayarlar."
type: docs
weight: 1800
url: /tr/net/aspose.svg.builder/svgbuilderextensions/onsuspend/
---
## SVGBuilderExtensions.OnSuspend<TBuilder> method

Medya veri yüklemesi askıya alındığında oluşan olayları işlemek üzere 'onsuspend' olay özniteliğini ayarlar.

```csharp
public static TBuilder OnSuspend<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Medya veri yüklemesi askıya alındığında çalıştırılacak JavaScript işlevi veya betiği. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
