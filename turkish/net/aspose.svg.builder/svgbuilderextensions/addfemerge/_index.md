---
title: "SVGBuilderExtensions.AddFeMerge"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddFeMerge yöntemi. Builder'a bir feMerge öğesi yapılandırması ekler. Bu öğe, filtre etkilerinin sıralı yerine eşzamanlı olarak uygulanmasını sağlar"
type: docs
weight: 240
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addfemerge/
---
## SVGBuilderExtensions.AddFeMerge<TBuilder> method

Yapıcıya bir 'feMerge' öğesi yapılandırması ekler. Bu öğe, filtre etkilerinin sıralı yerine eşzamanlı olarak uygulanmasını sağlar.

```csharp
public static TBuilder AddFeMerge<TBuilder>(this TBuilder builder, 
    Action<SVGFEMergeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'feMerge' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGFEMergeElementBuilder](../../svgfemergeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
