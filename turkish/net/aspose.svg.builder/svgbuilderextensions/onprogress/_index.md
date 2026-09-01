---
title: "SVGBuilderExtensions.OnProgress"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions OnProgress metodu. Devam eden bir sürecin ilerlemesini göstermek için olayları işlemek üzere onprogress olay özniteliğini ayarlar."
type: docs
weight: 1680
url: /tr/net/aspose.svg.builder/svgbuilderextensions/onprogress/
---
## SVGBuilderExtensions.OnProgress<TBuilder> method

Süreç ilerlemesini göstermek için olayları işlemek üzere 'onprogress' olay özniteliğini ayarlar.

```csharp
public static TBuilder OnProgress<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Devam eden bir sürecin ilerlemesini göstermek için yürütülecek JavaScript fonksiyonu veya betiği. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
