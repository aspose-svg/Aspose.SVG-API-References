---
title: "SVGBuilderExtensions.AddDesc"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddDesc yöntemi. Builder'a bir desc öğesi yapılandırması ekler. Desc öğesi, SVG içeriği için bir açıklama sağlamak amacıyla kullanılır."
type: docs
weight: 110
url: /tr/net/aspose.svg.builder/svgbuilderextensions/adddesc/
---
## SVGBuilderExtensions.AddDesc<TBuilder> method

'desc' öğesi yapılandırmasını oluşturucuya ekler. 'desc' öğesi, SVG içeriği için bir açıklama sağlamak amacıyla kullanılır.

```csharp
public static TBuilder AddDesc<TBuilder>(this TBuilder builder, 
    Action<SVGDescElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'desc' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGDescElementBuilder](../../svgdescelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
