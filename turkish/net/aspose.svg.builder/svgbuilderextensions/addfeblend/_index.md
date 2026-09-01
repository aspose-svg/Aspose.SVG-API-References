---
title: "SVGBuilderExtensions.AddFeBlend"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddFeBlend metodu. Builder'a bir feBlend öğesi yapılandırması ekler. Bu öğe iki grafik arasında bir karıştırma etkisi tanımlar."
type: docs
weight: 130
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addfeblend/
---
## AddFeBlend<TBuilder>(*this TBuilder, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend}

'feBlend' öğesi yapılandırmasını oluşturucuya ekler. Bu öğe, iki grafik arasındaki karıştırma etkisini tanımlar.

```csharp
public static TBuilder AddFeBlend<TBuilder>(this TBuilder builder, 
    Action<SVGFEBlendElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'feBlend' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGFEBlendElementBuilder](../../svgfeblendelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeBlend<TBuilder>(*this TBuilder, BlendMode?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend_1}

Karıştırma modunu ve filtre etkisi için çeşitli diğer özellikleri belirterek bir 'feBlend' öğesini SVG oluşturucuya ekler.

```csharp
public static TBuilder AddFeBlend<TBuilder>(this TBuilder builder, BlendMode? mode = default, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEBlendElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'feBlend' öğesinin ekleneceği SVG builder örneği. |
| mode | Kullanılacak karıştırma modu. İsteğe bağlı parametre. |
| in | Karıştırma etkisi için ilk giriş. Bir dize veya FilterInput olabilir. İsteğe bağlı parametre. |
| in2 | Karıştırma etkisi için ikinci giriş. Bir dize veya FilterInput olabilir. İsteğe bağlı parametre. |
| result | Bu filtre ilkel öğesi için sonuç tanımlayıcısı. İsteğe bağlı parametre. |
| x | Filtre ilkel öğesinin alt bölgesinin x koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| y | Filtre ilkel öğesinin alt bölgesinin y koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| width | Filtre ilkel öğesinin alt bölgesinin genişliği. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| yükseklik | Filtre ilkel alt bölgesinin yüksekliği. Bir double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| dolgu | Eleman için dolgu rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| çizgi | Eleman için çizgi rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| id | Filtre ilkel elemanının benzersiz tanımlayıcısı. İsteğe bağlı parametre. |
| genişlet | SVGFEBlendElementBuilder'ı daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* enum [BlendMode](../../blendmode/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEBlendElementBuilder](../../svgfeblendelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
