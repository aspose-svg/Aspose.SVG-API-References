---
title: "SVGBuilderExtensions.AddSet"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddSet yöntemi. Bir set öğesi yapılandırmasını oluşturucuya ekler"
type: docs
weight: 470
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addset/
---
## SVGBuilderExtensions.AddSet<TBuilder> method

Yapıcıya bir 'set' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddSet<TBuilder>(this TBuilder builder, 
    Action<SVGSetElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IBaseAnimationElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'set' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGSetElementBuilder](../../svgsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IBaseAnimationElementBuilder](../../ibaseanimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
