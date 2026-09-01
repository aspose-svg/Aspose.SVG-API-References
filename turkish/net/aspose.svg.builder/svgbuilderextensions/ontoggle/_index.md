---
title: "SVGBuilderExtensions.OnToggle"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions OnToggle yöntemi. Kullanıcı bir detay öğesi gibi bir kontrolü değiştirdiğinde olayları işlemek için ontoggle olay özniteliğini ayarlar"
type: docs
weight: 1820
url: /tr/net/aspose.svg.builder/svgbuilderextensions/ontoggle/
---
## SVGBuilderExtensions.OnToggle<TBuilder> method

Kullanıcı bir kontrolü, örneğin bir `details` öğesini değiştirdiğinde olayları işlemek için 'ontoggle' olay özniteliğini ayarlar.

```csharp
public static TBuilder OnToggle<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| value | Bir kontrol değiştirildiğinde çalıştırılacak JavaScript fonksiyonu veya betiği. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
