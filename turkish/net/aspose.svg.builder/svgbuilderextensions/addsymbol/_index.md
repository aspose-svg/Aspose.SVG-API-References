---
title: "SVGBuilderExtensions.AddSymbol"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddSymbol yöntemi. Bir symbol öğesi yapılandırmasını oluşturucuya ekler"
type: docs
weight: 520
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addsymbol/
---
## SVGBuilderExtensions.AddSymbol<TBuilder> method

Derleyiciye bir 'symbol' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddSymbol<TBuilder>(this TBuilder builder, 
    Action<SVGSymbolElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'symbol' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGSymbolElementBuilder](../../svgsymbolelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
