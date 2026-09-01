---
title: "SVGBuilderExtensions.Filter"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions Filter yöntemi. Özel bir yapılandırma kullanarak bir SVG öğesi için filter özniteliğini ayarlar"
type: docs
weight: 840
url: /tr/net/aspose.svg.builder/svgbuilderextensions/filter/
---
## SVGBuilderExtensions.Filter<TBuilder> method

Özel bir yapılandırma kullanarak bir SVG öğesi için 'filter' özniteliğini ayarlar.

```csharp
public static TBuilder Filter<TBuilder>(this TBuilder builder, 
    Action<FilterValueListBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | FilterValueListBuilder'ı yapılandırmak için bir temsilci. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [FilterValueListBuilder](../../filtervaluelistbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
