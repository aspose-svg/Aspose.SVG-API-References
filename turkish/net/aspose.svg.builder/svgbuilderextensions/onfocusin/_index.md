---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions OnFocusIn yöntemi. Öğede odaklanma olaylarını işlemek için onfocusin olay özniteliğini ayarlar."
type: docs
weight: 1450
url: /tr/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

'onfocusin' olay özniteliğini, öğedeki odak içine olaylarını işlemek için ayarlar.

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Öğe odak aldığında, genellikle 'onfocus' olayından önce çalıştırılacak JavaScript işlevi veya betiği. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

## Açıklamalar

'onfocusin' olayı, bir öğe odak almaya yaklaştığında tetiklenir. Bu olay, 'onfocus' olayından farklı olarak balonlamayı destekler ve alt öğelerdeki odak değişikliklerini de algılamak için kullanılabilir.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
