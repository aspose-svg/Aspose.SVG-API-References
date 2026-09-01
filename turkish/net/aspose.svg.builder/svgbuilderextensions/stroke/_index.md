---
title: "SVGBuilderExtensions.Stroke"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions Stroke yöntemi. Özel bir boya yapılandırması kullanarak bir SVG öğesi için stroke özniteliğini ayarlar"
type: docs
weight: 2080
url: /tr/net/aspose.svg.builder/svgbuilderextensions/stroke/
---
## Stroke<TBuilder>(*this TBuilder, Action&lt;PaintBuilder&gt;*) {#stroke_1}

Özel bir boya yapılandırması kullanarak bir SVG öğesi için 'stroke' özniteliğini ayarlar.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Action<PaintBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | Boyayı yapılandırmak için bir temsilci. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [PaintBuilder](../../paintbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Stroke<TBuilder>(*this TBuilder, Color*) {#stroke_2}

Belirli bir renk kullanarak bir SVG öğesi için 'stroke' özniteliğini ayarlar.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Color color)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| renk | Stroke için kullanılacak renk. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Stroke<TBuilder>(*this TBuilder, [Paint](../../paint/)*) {#stroke}

Önceden tanımlanmış bir boya değeri kullanarak bir SVG öğesi için 'stroke' özniteliğini ayarlar.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Paint paint)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| paint | Ayarlanacak boya değeri. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [Paint](../../paint/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
