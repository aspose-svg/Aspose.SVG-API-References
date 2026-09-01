---
title: "SVGBuilderExtensions.AddView"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddView yöntemi. Bir view öğesi yapılandırmasını oluşturucuya ekler"
type: docs
weight: 560
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addview/
---
## SVGBuilderExtensions.AddView<TBuilder> method

Derleyiciye bir 'view' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddView<TBuilder>(this TBuilder builder, 
    Action<SVGViewElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'view' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGViewElementBuilder](../../svgviewelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
