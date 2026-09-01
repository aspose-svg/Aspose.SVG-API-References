---
title: "SVGBuilderExtensions.StopColor"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions StopColor yöntemi. Bir SVG öğesinde bir degrade durak noktasındaki rengi tanımlayan stop-color özniteliğini ayarlar"
type: docs
weight: 2060
url: /tr/net/aspose.svg.builder/svgbuilderextensions/stopcolor/
---
## StopColor<TBuilder>(*this TBuilder, Color*) {#stopcolor_1}

SVG öğesi için 'stop-color' özniteliğini ayarlar, bir gradyan durağındaki rengi tanımlar.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| colorValue | Ayarlanacak renk değeri. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StopColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#stopcolor}

Özel bir renk yapılandırması kullanarak bir SVG öğesi için 'stop-color' özniteliğini ayarlar.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | Rengi yapılandırmak için bir temsilci. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
