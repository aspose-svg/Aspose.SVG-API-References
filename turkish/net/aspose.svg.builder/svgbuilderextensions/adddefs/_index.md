---
title: "SVGBuilderExtensions.AddDefs"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddDefs metodu. Builder'a bir defs tanımlama öğesi yapılandırması ekler."
type: docs
weight: 100
url: /tr/net/aspose.svg.builder/svgbuilderextensions/adddefs/
---
## SVGBuilderExtensions.AddDefs<TBuilder> method

'defs' (tanımlamalar) öğesi yapılandırmasını oluşturucuya ekler.

```csharp
public static TBuilder AddDefs<TBuilder>(this TBuilder builder, 
    Action<SVGDefsElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'defs' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGDefsElementBuilder](../../svgdefselementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
