---
title: "SVGBuilderExtensions.FloodColor"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions FloodColor yöntemi. Bir SVG öğesi için flood-color özniteliğini System.Drawing rengi kullanarak ayarlar"
type: docs
weight: 850
url: /tr/net/aspose.svg.builder/svgbuilderextensions/floodcolor/
---
## FloodColor<TBuilder>(*this TBuilder, Color*) {#floodcolor_1}

System.Drawing rengi kullanarak bir SVG öğesi için 'flood-color' özniteliğini ayarlar.

```csharp
public static TBuilder FloodColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| colorValue | Flood rengi olarak ayarlanacak renk. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FloodColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#floodcolor}

Özel bir renk yapılandırması kullanarak bir SVG öğesi için 'flood-color' özniteliğini ayarlar.

```csharp
public static TBuilder FloodColor<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | ColorBuilder'ı yapılandırmak için bir temsilci. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
