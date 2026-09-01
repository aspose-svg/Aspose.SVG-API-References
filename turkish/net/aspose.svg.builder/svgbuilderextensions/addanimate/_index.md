---
title: "SVGBuilderExtensions.AddAnimate"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddAnimate yöntemi. Oluşturucuya bir animate öğesi yapılandırması ekler."
type: docs
weight: 30
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addanimate/
---
## SVGBuilderExtensions.AddAnimate<TBuilder> method

Builder'a bir 'animate' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddAnimate<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IBaseAnimationElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'animate' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGAnimateElementBuilder](../../svganimateelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IBaseAnimationElementBuilder](../../ibaseanimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
