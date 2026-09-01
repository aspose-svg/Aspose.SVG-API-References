---
title: "SVGBuilderExtensions.AddTitle"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddTitle yöntemi. Oluşturucuya bir title öğesi yapılandırması ekler. Title öğesi, SVG içeriği için bir başlık sağlamak amacıyla kullanılır"
type: docs
weight: 540
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addtitle/
---
## SVGBuilderExtensions.AddTitle<TBuilder> method

Derleyiciye bir 'title' öğesi yapılandırması ekler. 'title' öğesi, SVG içeriği için bir başlık sağlamak amacıyla kullanılır.

```csharp
public static TBuilder AddTitle<TBuilder>(this TBuilder builder, 
    Action<SVGTitleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'title' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGTitleElementBuilder](../../svgtitleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
