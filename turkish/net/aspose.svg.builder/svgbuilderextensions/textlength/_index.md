---
title: "SVGBuilderExtensions.TextLength"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions TextLength yöntemi. Metin içeriğinin kesin uzunluğunu ayarlar"
type: docs
weight: 2220
url: /tr/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

Metin içeriğinin tam uzunluğunu ayarlar.

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Metnin uzunluğu. |
| tip | Değer için uzunluk birimi türü. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

## Açıklamalar

Bu yöntem, metin içeriğinin istenen uzunluğunu belirten 'textLength' özniteliğini ayarlar ve doğal metin uzunluğunu geçersiz kılabilir.

### Ayrıca Bakınız

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
