---
title: "SVGBuilderExtensions.AddPolyline"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddPolyline yöntemi. Bir polyline öğesi yapılandırmasını oluşturucuya ekler"
type: docs
weight: 430
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addpolyline/
---
## AddPolyline<TBuilder>(*this TBuilder, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline_1}

Yapıcıya bir 'polyline' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, 
    Action<SVGPolylineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'polyline' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolyline<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline}

SVG yapıcıya bir 'polyline' öğesi ekler, köşelerini ve stillerini belirtir.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolylineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'polyline' öğesinin ekleneceği SVG oluşturucu örneği. |
| points | Polyline'in noktalarını temsil eden (x ve y koordinatları dönüşümlü) double değerlerden oluşan bir dizi. |
| dolgu | Polyline için doldurma rengi veya boya stili. Bir Color, Paint enum değeri veya paint sunucu kimliği olabilir. İsteğe bağlı parametre. |
| çizgi | Polyline için kenar rengi veya boya stili. Bir Color, Paint enum değeri veya paint sunucu kimliği olabilir. İsteğe bağlı parametre. |
| id | Polyline öğesi için benzersiz tanımlayıcı. İsteğe bağlı parametre. |
| genişlet | Polyline öğesi oluşturucusunu daha fazla yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
