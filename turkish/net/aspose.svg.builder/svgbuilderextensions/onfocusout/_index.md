---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions OnFocusOut yöntemi. Öğede odak kaybı olaylarını işlemek için onfocusout olay özniteliğini ayarlar"
type: docs
weight: 1460
url: /tr/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

'onfocusout' olay özniteliğini, öğedeki odak dışına olaylarını işlemek için ayarlar.

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Öğenin odak kaybettiğinde çalıştırılacak JavaScript işlevi veya betiği, genellikle 'onblur' olayından önce. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

## Açıklamalar

'onfocusout' olayı, bir öğenin odak kaybetmek üzere olduğu zaman tetiklenir. 'onfocusin' olayına benzer şekilde, bu olay kabarcıklanmayı destekler ve alt öğelerdeki odak değişikliklerini tespit etmek için de kullanılabilir.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
