---
title: "SVGBuilderExtensions.AddMask"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddMask yöntemi. Builder'a bir mask öğesi yapılandırması ekler."
type: docs
weight: 380
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addmask/
---
## SVGBuilderExtensions.AddMask<TBuilder> method

Yapıcıya bir 'mask' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddMask<TBuilder>(this TBuilder builder, 
    Action<SVGMaskElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'mask' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGMaskElementBuilder](../../svgmaskelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
