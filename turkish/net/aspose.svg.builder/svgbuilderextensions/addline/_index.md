---
title: "SVGBuilderExtensions.AddLine"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddLine yöntemi. Bir satır öğesi yapılandırmasını oluşturucuya ekler"
type: docs
weight: 350
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addline/
---
## AddLine<TBuilder>(*this TBuilder, Action&lt;SVGLineElementBuilder&gt;*) {#addline_1}

Yapıcıya bir 'line' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    Action<SVGLineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'line' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLine<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGLineElementBuilder&gt;*) {#addline}

SVG yapıcıya belirtilen başlangıç ve bitiş noktaları ve stillerle bir 'line' öğesi ekler.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1 = null, OneOf<double, (double, LengthType)> y1 = null, 
    OneOf<double, (double, LengthType)> x2 = null, OneOf<double, (double, LengthType)> y2 = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGLineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'line' öğesinin ekleneceği SVG oluşturucu örneği. |
| x1 | Satırın başlangıç noktasının x koordinatı. Çift (double) bir değer veya double ve LengthType ikilisinden oluşan bir tuple olabilir. |
| y1 | Satırın başlangıç noktasının y koordinatı. Çift (double) bir değer veya double ve LengthType ikilisinden oluşan bir tuple olabilir. |
| x2 | Satırın bitiş noktasının x koordinatı. Çift (double) bir değer veya double ve LengthType ikilisinden oluşan bir tuple olabilir. |
| y2 | Satırın bitiş noktasının y koordinatı. Çift (double) bir değer veya double ve LengthType ikilisinden oluşan bir tuple olabilir. |
| dolgu | Satır için dolgu rengi veya boya stili. Bir Color, Paint enum değeri veya paint server kimliği olabilir. İsteğe bağlı parametre. |
| çizgi | Satır için çizgi (stroke) rengi veya boya stili. Bir Color, Paint enum değeri veya paint server kimliği olabilir. İsteğe bağlı parametre. |
| id | Satır öğesi için benzersiz tanımlayıcı. İsteğe bağlı parametre. |
| genişlet | Satır öğesi oluşturucusunu daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
