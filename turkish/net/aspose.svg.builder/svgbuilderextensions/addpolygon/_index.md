---
title: "SVGBuilderExtensions.AddPolygon"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddPolygon yöntemi. Oluşturucuya bir çokgen öğesi yapılandırması ekler"
type: docs
weight: 420
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addpolygon/
---
## AddPolygon<TBuilder>(*this TBuilder, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon_1}

Yapıcıya bir 'polygon' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, 
    Action<SVGPolygonElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'polygon' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolygon<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon}

SVG yapıcıya bir 'polygon' öğesi ekler, köşelerini ve stillerini belirtir.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolygonElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'polygon' öğesinin ekleneceği SVG oluşturucu örneği. |
| points | Poligonun noktalarını temsil eden double değerlerinden oluşan bir dizi (x ve y koordinatları dönüşümlü). |
| dolgu | Poligon için dolgu rengi veya boya stili. Bir Color veya Paint enum değeri ya da paint sunucu kimliği olabilir. İsteğe bağlı parametre. |
| çizgi | Poligon için kenar rengi veya boya stili. Bir Color veya Paint enum değeri ya da paint sunucu kimliği olabilir. İsteğe bağlı parametre. |
| id | Poligon öğesi için benzersiz tanımlayıcı. İsteğe bağlı parametre. |
| genişlet | Poligon öğesi oluşturucusunu daha fazla yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
