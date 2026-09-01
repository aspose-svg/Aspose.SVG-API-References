---
title: "SVGBuilderExtensions.Rect"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions Rect yöntemi. Bir SVG öğesi için bir dikdörtgen tanımlamak amacıyla x, y, genişlik ve yükseklik özniteliklerini ayarlar."
type: docs
weight: 1920
url: /tr/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

Bir SVG öğesi için bir dikdörtgen tanımlamak amacıyla 'x', 'y', 'width' ve 'height' özniteliklerini ayarlar.

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| x | Dikdörtgenin x koordinatı. |
| y | Dikdörtgenin y koordinatı. |
| width | Dikdörtgenin genişliği. |
| yükseklik | Dikdörtgenin yüksekliği. |
| tip | Tüm boyutlar için uzunluk ölçüm tipi (varsayılan pikseldir). |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
