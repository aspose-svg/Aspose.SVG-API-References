---
title: "SVGBuilderExtensions.AddRect"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddRect yöntemi. Oluşturucuya bir rect öğesi yapılandırması ekler."
type: docs
weight: 450
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addrect/
---
## AddRect<TBuilder>(*this TBuilder, Action&lt;SVGRectElementBuilder&gt;*) {#addrect_1}

Yapıcıya bir 'rect' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    Action<SVGRectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'rect' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRect<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGRectElementBuilder&gt;*) {#addrect}

SVG yapıcıya belirtilen boyut ve stillerle bir 'rect' (dikdörtgen) öğesi ekler.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGRectElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'rect' öğesinin ekleneceği SVG oluşturucu örneği. |
| x | Dikdörtgenin başlangıç noktasının x koordinatı. Çift (double) bir değer veya çift ve LengthType ikilisinden oluşan bir tuple olabilir. |
| y | Dikdörtgenin başlangıç noktasının y koordinatı. Çift (double) bir değer veya çift ve LengthType ikilisinden oluşan bir tuple olabilir. |
| width | Dikdörtgenin genişliği. Çift (double) bir değer veya çift ve LengthType ikilisinden oluşan bir tuple olabilir. |
| yükseklik | Dikdörtgenin yüksekliği. Çift (double) bir değer veya çift ve LengthType ikilisinden oluşan bir tuple olabilir. |
| dolgu | Dikdörtgenin doldurma rengi veya boya stili. Bir Color, Paint enum değeri veya paint sunucu kimliği olabilir. İsteğe bağlı parametre. |
| çizgi | Dikdörtgenin kenar çizgi rengi veya boya stili. Bir Color, Paint enum değeri veya paint sunucu kimliği olabilir. İsteğe bağlı parametre. |
| id | Dikdörtgen öğesi için benzersiz tanımlayıcı. İsteğe bağlı parametre. |
| genişlet | Dikdörtgen öğesi oluşturucusunu daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
