---
title: "SVGBuilderExtensions.Mask"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions Mask yöntemi. Özel bir mask yapılandırması kullanarak bir SVG öğesi için mask özniteliğini ayarlar."
type: docs
weight: 1150
url: /tr/net/aspose.svg.builder/svgbuilderextensions/mask/
---
## SVGBuilderExtensions.Mask<TBuilder> method

Özel bir maske yapılandırması kullanarak bir SVG öğesi için 'mask' özniteliğini ayarlar.

```csharp
public static TBuilder Mask<TBuilder>(this TBuilder builder, Action<MaskBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | Maskeyi yapılandırmak için bir temsilci. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [MaskBuilder](../../maskbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
