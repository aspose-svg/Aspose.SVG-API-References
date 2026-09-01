---
title: "SVGBuilderExtensions.AddFeImage"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddFeImage yöntemi. Oluşturucuya bir feImage öğesi yapılandırması ekler. Bu öğe harici bir görüntüyü alır ve filtre işlem hattına dahil eder"
type: docs
weight: 230
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addfeimage/
---
## AddFeImage<TBuilder>(*this TBuilder, Action&lt;SVGFEImageElementBuilder&gt;*) {#addfeimage}

Yapıcıya bir 'feImage' öğesi yapılandırması ekler. Bu öğe harici bir görüntüyü alır ve filtre işlem hattına dahil eder.

```csharp
public static TBuilder AddFeImage<TBuilder>(this TBuilder builder, 
    Action<SVGFEImageElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'feImage' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGFEImageElementBuilder](../../svgfeimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeImage<TBuilder>(*this TBuilder, string, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEImageElementBuilder&gt;*) {#addfeimage_1}

SVG yapıcıya bir 'feImage' öğesi ekler, harici bir görüntüyü filtre etkisine dahil eder.

```csharp
public static TBuilder AddFeImage<TBuilder>(this TBuilder builder, string href = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEImageElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'feImage' öğesinin ekleneceği SVG oluşturucu örneği. |
| href | Harici görüntünün URL'si veya referansı. İsteğe bağlı parametre. |
| result | Bu filtre ilkel öğesi için sonuç tanımlayıcısı. İsteğe bağlı parametre. |
| x | Filtre ilkel öğesinin alt bölgesinin x koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| y | Filtre ilkel öğesinin alt bölgesinin y koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| width | Filtre ilkel öğesinin alt bölgesinin genişliği. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| yükseklik | Filtre ilkel alt bölgesinin yüksekliği. Bir double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| dolgu | Eleman için dolgu rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| çizgi | Eleman için çizgi rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| id | Filtre ilkel elemanının benzersiz tanımlayıcısı. İsteğe bağlı parametre. |
| genişlet | SVGFEImageElementBuilder'ı daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEImageElementBuilder](../../svgfeimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
