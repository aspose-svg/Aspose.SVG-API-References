---
title: "SVGBuilderExtensions.SetPreserveAspectRatio"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions SetPreserveAspectRatio yöntemi. Bir SVG öğesi için preserveAspectRatio özniteliğini ayarlar."
type: docs
weight: 2020
url: /tr/net/aspose.svg.builder/svgbuilderextensions/setpreserveaspectratio/
---
## SVGBuilderExtensions.SetPreserveAspectRatio<TBuilder> method

SVG öğesi için 'preserveAspectRatio' özniteliğini ayarlar.

```csharp
public static TBuilder SetPreserveAspectRatio<TBuilder>(this TBuilder builder, 
    AspectRatioAlign align, AspectRatioScaling meetOrSlice = AspectRatioScaling.Meet)
    where TBuilder : ISVGElementBuilder, IPreserveAspectRatioAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| align | En‑boy oranı için hizalama ayarı. |
| meetOrSlice | En‑boy oranının nasıl korunduğunu belirtir (varsayılan 'Meet' dir). |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [AspectRatioAlign](../../aspectratioalign/)
* enum [AspectRatioScaling](../../aspectratioscaling/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../../ipreserveaspectratioattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
