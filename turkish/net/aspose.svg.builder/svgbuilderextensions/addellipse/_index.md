---
title: "SVGBuilderExtensions.AddEllipse"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddEllipse yöntemi. Oluşturucuya bir elips öğesi yapılandırması ekler."
type: docs
weight: 120
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addellipse/
---
## AddEllipse<TBuilder>(*this TBuilder, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse_1}

'ellipse' öğesi yapılandırmasını oluşturucuya ekler.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    Action<SVGEllipseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'ellipse' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddEllipse<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse}

Merkez, yarıçaplar ve stillerini belirterek bir 'ellipse' öğesini SVG oluşturucuya ekler.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> rx = null, OneOf<double, (double, LengthType)> ry = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGEllipseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'ellipse' öğesinin ekleneceği SVG builder örneği. |
| cx | Elipsin merkezinin x koordinatı. Çift (double) bir değer veya çift ve LengthType içeren bir tuple olabilir. |
| cy | Elipsin merkezinin y koordinatı. Çift (double) bir değer veya çift ve LengthType içeren bir tuple olabilir. |
| rx | Elipsin x yarıçapı. Çift (double) bir değer veya çift ve LengthType içeren bir tuple olabilir. |
| ry | Elipsin y yarıçapı. Çift (double) bir değer veya çift ve LengthType içeren bir tuple olabilir. |
| dolgu | Elipsin doldurma rengi veya boya stili. Color, Paint enum değeri veya paint sunucu kimliği olabilir. İsteğe bağlı parametre. |
| çizgi | Elipsin kontur rengi veya boya stili. Color, Paint enum değeri veya paint sunucu kimliği olabilir. İsteğe bağlı parametre. |
| id | Elips öğesi için benzersiz tanımlayıcı. İsteğe bağlı parametre. |
| genişlet | Elips öğesi oluşturucusunu daha fazla yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
