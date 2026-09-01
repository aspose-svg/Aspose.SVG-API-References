---
title: "SVGBuilderExtensions.OnWaiting"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions OnWaiting yöntemi. Veri tamponlaması nedeniyle medya oynatımı geciktiğinde olayları işlemek için onwaiting olay özniteliğini ayarlar."
type: docs
weight: 1850
url: /tr/net/aspose.svg.builder/svgbuilderextensions/onwaiting/
---
## SVGBuilderExtensions.OnWaiting<TBuilder> method

Veri tamponlaması nedeniyle medya oynatımı geciktiğinde olayları işlemek için 'onwaiting' olay özniteliğini ayarlar.

```csharp
public static TBuilder OnWaiting<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Medya oynatımı tamponlama nedeniyle geciktiğinde çalıştırılacak JavaScript işlevi veya betiği. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
