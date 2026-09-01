---
title: "SVGBuilderExtensions.OnCopy"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions OnCopy yöntemi. SVG öğesinden içerik kopyalandığında çalıştırılacak bir betiği tanımlayan oncopy olay özniteliğini ayarlar."
type: docs
weight: 1270
url: /tr/net/aspose.svg.builder/svgbuilderextensions/oncopy/
---
## SVGBuilderExtensions.OnCopy<TBuilder> method

'oncopy' olay özniteliğini ayarlar, içeriğin SVG öğesinden kopyalandığında çalışacak bir betik tanımlayarak.

```csharp
public static TBuilder OnCopy<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Kopyalama olayında çalıştırılacak JavaScript işlevi veya betiği. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
