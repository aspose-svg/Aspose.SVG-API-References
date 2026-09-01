---
title: "SVGBuilderExtensions.OnCut"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions OnCut yöntemi. SVG öğesinden içerik kesildiğinde çalıştırılacak bir betiği tanımlayan oncut olay özniteliğini ayarlar"
type: docs
weight: 1290
url: /tr/net/aspose.svg.builder/svgbuilderextensions/oncut/
---
## SVGBuilderExtensions.OnCut<TBuilder> method

'oncut' olay özniteliğini ayarlar, içeriğin SVG öğesinden kesildiğinde çalışacak bir betik tanımlayarak.

```csharp
public static TBuilder OnCut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Kesme olayında çalıştırılacak JavaScript işlevi veya betiği. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
