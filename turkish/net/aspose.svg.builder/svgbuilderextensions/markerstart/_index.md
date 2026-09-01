---
title: "SVGBuilderExtensions.MarkerStart"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions MarkerStart yöntemi. Bir SVG öğesi için yolu başlangıcında işaretleyiciyi belirten marker-start özniteliğini ayarlar."
type: docs
weight: 1140
url: /tr/net/aspose.svg.builder/svgbuilderextensions/markerstart/
---
## MarkerStart<TBuilder>(*this TBuilder, string*) {#markerstart_1}

Bir SVG öğesi için 'marker-start' özniteliğini ayarlar, işareti yolun başlangıcında belirterek.

```csharp
public static TBuilder MarkerStart<TBuilder>(this TBuilder builder, string markerId)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| markerId | Kullanılacak işaretleyicinin kimliği. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## MarkerStart<TBuilder>(*this TBuilder, [MarkerPos](../../markerpos/)*) {#markerstart}

Önceden tanımlanmış bir işaret konumu kullanarak bir SVG öğesi için 'marker-start' özniteliğini ayarlar.

```csharp
public static TBuilder MarkerStart<TBuilder>(this TBuilder builder, MarkerPos value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| value | Ayarlanacak işaretleyici konum değeri. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* enum [MarkerPos](../../markerpos/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
