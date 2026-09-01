---
title: "SVGBuilderExtensions.AddFeSpecularLighting"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddFeSpecularLighting yöntemi. Oluşturucuya bir feSpecularLighting öğesi yapılandırması ekler. Bu öğe, görüntüye speküler yansıma taklit eden bir aydınlatma etkisi uygular"
type: docs
weight: 270
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addfespecularlighting/
---
## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_2}

Yapıcıya bir 'feSpecularLighting' öğesi yapılandırması ekler. Bu öğe, görüntüye bir aydınlatma etkisi uygular ve speküler yansıma taklit eder.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpecularLightingElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'feSpecularLighting' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDistantLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting}

SVG yapıcıya bir 'feSpecularLighting' öğesi ekler, belirtilen bir ışık kaynağı kullanarak speküler aydınlatma etkisi uygular.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDistantLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'feSpecularLighting' öğesinin ekleneceği SVG oluşturucu örneği. |
| lightSource | Yansımalı aydınlatma etkisi için ışık kaynağını yapılandıran bir eylem. |
| lightingColor | Işığın rengi. İsteğe bağlı parametre. |
| surfaceScale | Aydınlatma etkisi için yüzey ölçek faktörü. İsteğe bağlı parametre. |
| specularConstant | Yansıma terimini ölçeklemek için kullanılan sabit. İsteğe bağlı parametre. |
| specularExponent | Yansıma teriminin üssü, yansıma vurgusunun odak noktasını kontrol eder. İsteğe bağlı parametre. |
| kernelUnitLength | Konvolüsyon filtresi için çekirdek birim uzunluğu. Çift tipinde bir değer ya da iki çift değer içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| in | Yansımalı aydınlatma etkisinin uygulanacağı giriş görüntüsü. Bir dize ya da FilterInput olabilir. İsteğe bağlı parametre. |
| result | Bu filtre ilkel öğesi için sonuç tanımlayıcısı. İsteğe bağlı parametre. |
| x | Filtre ilkel öğesinin alt bölgesinin x koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| y | Filtre ilkel öğesinin alt bölgesinin y koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| width | Filtre ilkel öğesinin alt bölgesinin genişliği. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| yükseklik | Filtre ilkel alt bölgesinin yüksekliği. Bir double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| dolgu | Eleman için dolgu rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| çizgi | Eleman için çizgi rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| id | Filtre ilkel elemanının benzersiz tanımlayıcısı. İsteğe bağlı parametre. |
| genişlet | SVGFESpecularLightingElementBuilder'ı daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGFEDistantLightElementBuilder](../../svgfedistantlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEPointLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_1}

SVG yapıcıya bir 'feSpecularLighting' öğesi ekler, belirtilen bir ışık kaynağı kullanarak speküler aydınlatma etkisi uygular.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEPointLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'feSpecularLighting' öğesinin ekleneceği SVG oluşturucu örneği. |
| lightSource | Yansımalı aydınlatma etkisi için ışık kaynağını yapılandıran bir eylem. |
| lightingColor | Işığın rengi. İsteğe bağlı parametre. |
| surfaceScale | Aydınlatma etkisi için yüzey ölçek faktörü. İsteğe bağlı parametre. |
| specularConstant | Yansıma terimini ölçeklemek için kullanılan sabit. İsteğe bağlı parametre. |
| specularExponent | Yansıma teriminin üssü, yansıma vurgusunun odak noktasını kontrol eder. İsteğe bağlı parametre. |
| kernelUnitLength | Konvolüsyon filtresi için çekirdek birim uzunluğu. Çift tipinde bir değer ya da iki çift değer içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| in | Yansımalı aydınlatma etkisinin uygulanacağı giriş görüntüsü. Bir dize ya da FilterInput olabilir. İsteğe bağlı parametre. |
| result | Bu filtre ilkel öğesi için sonuç tanımlayıcısı. İsteğe bağlı parametre. |
| x | Filtre ilkel öğesinin alt bölgesinin x koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| y | Filtre ilkel öğesinin alt bölgesinin y koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| width | Filtre ilkel öğesinin alt bölgesinin genişliği. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| yükseklik | Filtre ilkel alt bölgesinin yüksekliği. Bir double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| dolgu | Eleman için dolgu rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| çizgi | Eleman için çizgi rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| id | Filtre ilkel elemanının benzersiz tanımlayıcısı. İsteğe bağlı parametre. |
| genişlet | SVGFESpecularLightingElementBuilder'ı daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGFEPointLightElementBuilder](../../svgfepointlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpotLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_3}

SVG yapıcıya bir 'feSpecularLighting' öğesi ekler, belirtilen bir ışık kaynağı kullanarak speküler aydınlatma etkisi uygular.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpotLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'feSpecularLighting' öğesinin ekleneceği SVG oluşturucu örneği. |
| lightSource | Yansımalı aydınlatma etkisi için ışık kaynağını yapılandıran bir eylem. |
| lightingColor | Işığın rengi. İsteğe bağlı parametre. |
| surfaceScale | Aydınlatma etkisi için yüzey ölçek faktörü. İsteğe bağlı parametre. |
| specularConstant | Yansıma terimini ölçeklemek için kullanılan sabit. İsteğe bağlı parametre. |
| specularExponent | Yansıma teriminin üssü, yansıma vurgusunun odak noktasını kontrol eder. İsteğe bağlı parametre. |
| kernelUnitLength | Konvolüsyon filtresi için çekirdek birim uzunluğu. Çift tipinde bir değer ya da iki çift değer içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| in | Yansımalı aydınlatma etkisinin uygulanacağı giriş görüntüsü. Bir dize ya da FilterInput olabilir. İsteğe bağlı parametre. |
| result | Bu filtre ilkel öğesi için sonuç tanımlayıcısı. İsteğe bağlı parametre. |
| x | Filtre ilkel öğesinin alt bölgesinin x koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| y | Filtre ilkel öğesinin alt bölgesinin y koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| width | Filtre ilkel öğesinin alt bölgesinin genişliği. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| yükseklik | Filtre ilkel alt bölgesinin yüksekliği. Bir double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| dolgu | Eleman için dolgu rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| çizgi | Eleman için çizgi rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| id | Filtre ilkel elemanının benzersiz tanımlayıcısı. İsteğe bağlı parametre. |
| genişlet | SVGFESpecularLightingElementBuilder'ı daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGFESpotLightElementBuilder](../../svgfespotlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
