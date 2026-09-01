---
title: "SVGBuilderExtensions.AddFeDropShadow"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddFeDropShadow yöntemi. Builder'a bir feDropShadow öğesi yapılandırması ekler. Bu öğe gölge efekti oluşturur"
type: docs
weight: 200
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addfedropshadow/
---
## AddFeDropShadow<TBuilder>(*this TBuilder, Action&lt;SVGFEDropShadowElementBuilder&gt;*) {#addfedropshadow}

'feDropShadow' öğesi yapılandırmasını oluşturucuya ekler. Bu öğe, bir gölge efekti oluşturur.

```csharp
public static TBuilder AddFeDropShadow<TBuilder>(this TBuilder builder, 
    Action<SVGFEDropShadowElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'feDropShadow' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGFEDropShadowElementBuilder](../../svgfedropshadowelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDropShadow<TBuilder>(*this TBuilder, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDropShadowElementBuilder&gt;*) {#addfedropshadow_1}

Giriş grafiği için bir gölge efekti oluşturarak bir 'feDropShadow' öğesini SVG oluşturucuya ekler.

```csharp
public static TBuilder AddFeDropShadow<TBuilder>(this TBuilder builder, double? dx = null, 
    double? dy = null, OneOf<double, (double, double)> stdDeviation = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDropShadowElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'feDropShadow' öğesinin ekleneceği SVG builder örneği. |
| dx | Gölge için yatay ofset. İsteğe bağlı parametre. |
| dy | Gölge için dikey ofset. İsteğe bağlı parametre. |
| stdDeviation | Gölgedeki bulanıklaştırma işlemi için standart sapma. Bir double veya iki double içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| in | Gölgenin uygulanacağı giriş grafiği. Bir string veya FilterInput olabilir. İsteğe bağlı parametre. |
| result | Bu filtre ilkel öğesi için sonuç tanımlayıcısı. İsteğe bağlı parametre. |
| x | Filtre ilkel öğesinin alt bölgesinin x koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| y | Filtre ilkel öğesinin alt bölgesinin y koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| width | Filtre ilkel öğesinin alt bölgesinin genişliği. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| yükseklik | Filtre ilkel alt bölgesinin yüksekliği. Bir double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| dolgu | Eleman için dolgu rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| çizgi | Eleman için çizgi rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| id | Filtre ilkel elemanının benzersiz tanımlayıcısı. İsteğe bağlı parametre. |
| genişlet | SVGFEDropShadowElementBuilder'ı daha fazla yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDropShadowElementBuilder](../../svgfedropshadowelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
