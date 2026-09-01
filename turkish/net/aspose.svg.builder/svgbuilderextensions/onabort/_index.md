---
title: "SVGBuilderExtensions.OnAbort"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions OnAbort yöntemi. Bir SVG belgesinin yüklemesi iptal edildiğinde çalıştırılacak bir betiği tanımlayan onabort olay özniteliğini ayarlar."
type: docs
weight: 1190
url: /tr/net/aspose.svg.builder/svgbuilderextensions/onabort/
---
## SVGBuilderExtensions.OnAbort<TBuilder> method

'onabort' olay özniteliğini ayarlar, bir SVG belgesinin yüklemesi iptal edildiğinde çalışacak bir betik tanımlayarak.

```csharp
public static TBuilder OnAbort<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Belge yüklemesi iptal edildiğinde çalıştırılacak JavaScript fonksiyonu veya betiği. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
