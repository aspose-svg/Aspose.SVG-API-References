---
title: "SVGBuilderExtensions.AddMetadata"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddMetadata yöntemi. Oluşturucuya bir metadata öğesi yapılandırması ekler. Metadata öğesi, SVG içeriğine metadata eklemek için kullanılır."
type: docs
weight: 390
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

Yapıcıya bir 'metadata' öğesi yapılandırması ekler. 'metadata' öğesi, SVG içeriğine meta veriler eklemek için kullanılır.

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| TElement | SVG modelindeki 'metadata' öğesini temsil eden tip. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'metadata' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
