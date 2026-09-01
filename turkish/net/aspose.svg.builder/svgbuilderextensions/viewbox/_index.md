---
title: "SVGBuilderExtensions.ViewBox"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions ViewBox yöntemi. Bir SVG öğesi için viewBox özniteliğini ayarlar."
type: docs
weight: 2300
url: /tr/net/aspose.svg.builder/svgbuilderextensions/viewbox/
---
## SVGBuilderExtensions.ViewBox<TBuilder> method

Bir SVG öğesi için 'viewBox' özniteliğini ayarlar.

```csharp
public static TBuilder ViewBox<TBuilder>(this TBuilder builder, double minX, double minY, 
    double width, double height)
    where TBuilder : ISVGElementBuilder, IViewBoxAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| minX | viewBox'ın minimum X koordinatı. |
| minY | viewBox'ın minimum Y koordinatı. |
| width | viewBox'ın genişliği. |
| yükseklik | viewBox'ın yüksekliği. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IViewBoxAttributeSetter](../../iviewboxattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
