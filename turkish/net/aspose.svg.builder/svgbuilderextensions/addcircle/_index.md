---
title: "SVGBuilderExtensions.AddCircle"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddCircle yöntemi. Bir daire öğesi yapılandırmasını oluşturucuya ekler."
type: docs
weight: 70
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addcircle/
---
## AddCircle<TBuilder>(*this TBuilder, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle_1}

'circle' öğesi yapılandırmasını oluşturucuya ekler.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    Action<SVGCircleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | Daire öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddCircle<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle}

Belirtilen merkez, yarıçap ve stillerle bir 'circle' öğesini SVG oluşturucuya ekler.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGCircleElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | Daire öğesinin ekleneceği SVG oluşturucu örneği. |
| cx | Dairenin merkezinin x koordinatı. Çift bir değer veya çift ve LengthType ikilisi olabilir. |
| cy | Dairenin merkezinin y koordinatı. Çift bir değer veya çift ve LengthType ikilisi olabilir. |
| r | Dairenin yarıçapı. Çift bir değer veya çift ve LengthType ikilisi olabilir. |
| dolgu | Dairenin dolgu rengi veya boya stili. Bir Color, Paint enum değeri veya paint server kimliği olabilir. İsteğe bağlı parametre. |
| çizgi | Dairenin kenar çizgi rengi veya boya stili. Bir Color, Paint enum değeri veya paint server kimliği olabilir. İsteğe bağlı parametre. |
| id | Daire öğesi için benzersiz tanımlayıcı. İsteğe bağlı parametre. |
| genişlet | Daire öğesi oluşturucusunu daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
