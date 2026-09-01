---
title: "SVGBuilderExtensions.AddFilter"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddFilter yöntemi. Builder'a bir filtre öğesi yapılandırması ekler."
type: docs
weight: 300
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

Yapıcıya bir 'filter' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | ‘filter’ öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

SVG yapıcıya bir 'filter' öğesi ekler, SVG öğelerine uygulanabilen bir filtre etkisi tanımlar.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | ‘filter’ öğesinin ekleneceği SVG builder örneği. |
| filterUnits | Filtrenin x, y, genişlik ve yükseklik öznitelikleri için koordinat sistemini belirtir. İsteğe bağlı parametre. |
| primitiveUnits | Filtrenin alt öğelerinin öznitelikleri için koordinat sistemini belirtir. İsteğe bağlı parametre. |
| x | Filtre bölgesinin x koordinatı. Double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| y | Filtre bölgesinin y koordinatı. Double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| width | Filtre bölgesinin genişliği. Double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| yükseklik | Filtre bölgesinin yüksekliği. Double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| dolgu | Filtre öğesi için doldurma rengi veya boya. İsteğe bağlı parametre. |
| çizgi | Filtre öğesi için çizgi rengi veya boya. İsteğe bağlı parametre. |
| id | Filtre öğesi için benzersiz tanımlayıcı. İsteğe bağlı parametre. |
| genişlet | SVGFilterElementBuilder'ı daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
