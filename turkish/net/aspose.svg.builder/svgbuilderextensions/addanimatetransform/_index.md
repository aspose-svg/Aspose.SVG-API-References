---
title: "SVGBuilderExtensions.AddAnimateTransform"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddAnimateTransform yöntemi. Builder'a bir animateTransform öğesi yapılandırması ekler."
type: docs
weight: 50
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addanimatetransform/
---
## SVGBuilderExtensions.AddAnimateTransform<TBuilder> method

Builder'a bir 'animateTransform' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddAnimateTransform<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateTransformElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'animateTransform' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGAnimateTransformElementBuilder](../../svganimatetransformelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationElementBuilder](../../ianimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
