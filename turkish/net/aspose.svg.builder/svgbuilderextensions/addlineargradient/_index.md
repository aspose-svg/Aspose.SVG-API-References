---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddLinearGradient yöntemi. Oluşturucuya bir linearGradient öğesi yapılandırması ekler"
type: docs
weight: 360
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

Yapıcıya bir 'linearGradient' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'linearGradient' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

SVG yapıcıya bir 'linearGradient' öğesi ekler, başlangıç ve bitiş konumlarını ve diğer degrade özelliklerini belirtir.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'linearGradient' öğesinin ekleneceği SVG oluşturucu örneği. |
| x1 | Gradyan için başlangıç x koordinatı. Double veya LengthType içeren bir ValueTuple olabilir. |
| y1 | Gradyan için başlangıç y koordinatı. Double veya LengthType içeren bir ValueTuple olabilir. |
| x2 | Gradyan için bitiş x koordinatı. Double veya LengthType içeren bir ValueTuple olabilir. |
| y2 | Gradyan için bitiş y koordinatı. Double veya LengthType içeren bir ValueTuple olabilir. |
| gradientUnits | Gradyan için koordinat sistemini belirtir. İsteğe bağlı parametre. |
| spreadMethod | Gradyanın başlangıç ve bitiş noktalarının ötesinde nasıl yayıldığını tanımlar. İsteğe bağlı parametre. |
| href | Uygulanabiliyorsa, başka bir degradeye referans. İsteğe bağlı parametre. |
| id | Degrade öğesi için benzersiz tanımlayıcı. İsteğe bağlı parametre. |
| genişlet | Linear gradient öğesi oluşturucusunu daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
