---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddRadialGradient yöntemi. Builder'a bir radialGradient öğesi yapılandırması ekler"
type: docs
weight: 440
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

Yapıcıya bir 'radialGradient' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'radialGradient' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

SVG yapıcıya bir 'radialGradient' öğesi ekler, merkezini, yarıçapını ve odak noktalarını, ayrıca diğer degrade özelliklerini belirtir.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'radialGradient' öğesinin ekleneceği SVG builder örneği. |
| cx | Gradyanın merkezinin x koordinatı. Double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| cy | Gradyanın merkezinin y koordinatı. Double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| r | Gradyanın yarıçapı. Double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| fx | Gradyanın odak noktasının x koordinatı. Double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| fy | Gradyanın odak noktasının y koordinatı. Double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| gradientUnits | Gradyan için koordinat sistemini belirtir. İsteğe bağlı parametre. |
| spreadMethod | Gradyanın başlangıç ve bitiş noktalarının ötesinde nasıl yayıldığını tanımlar. İsteğe bağlı parametre. |
| href | Uygulanabiliyorsa, başka bir degradeye referans. İsteğe bağlı parametre. |
| id | Degrade öğesi için benzersiz tanımlayıcı. İsteğe bağlı parametre. |
| genişlet | Radial degrade öğesi oluşturucusunu daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
