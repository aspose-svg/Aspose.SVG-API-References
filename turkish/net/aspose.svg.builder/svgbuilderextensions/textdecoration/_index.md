---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions TextDecoration yöntemi. Metne eklenen süslemeleri tanımlayan bir SVG öğesi için text-decoration özniteliğini ayarlar"
type: docs
weight: 2210
url: /tr/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

Bir SVG öğesi için 'text-decoration' özniteliğini ayarlar, metne eklenen süslemeleri tanımlar.

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| altçizgi | Metnin altı çizili olup olmadığını belirtir. |
| üstçizgi | Metnin üstü çizili olup olmadığını belirtir. |
| üstüçizili | Metnin üzerinden bir çizgi geçip geçmeyeceğini belirtir. |
| yanıp sönen | Metnin yanıp sönüp sönmeyeceğini belirtir (kullanımı önerilmez). |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
