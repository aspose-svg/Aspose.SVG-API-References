---
title: "SVGBuilderExtensions.AddFeDiffuseLighting"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddFeDiffuseLighting metodu. Builder'a bir feDiffuseLighting öğesi yapılandırması ekler. Bu öğe bir görüntüye aydınlatma etkisi sağlar"
type: docs
weight: 180
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addfediffuselighting/
---
## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting}

'feDiffuseLighting' öğesi yapılandırmasını oluşturucuya ekler. Bu öğe, bir görüntüye aydınlatma etkisi sağlar.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDiffuseLightingElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'feDiffuseLighting' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDistantLightElementBuilder&gt;, Color?, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting_1}

Belirtilen bir ışık kaynağı kullanarak difüz aydınlatma etkisi uygulayan bir 'feDiffuseLighting' öğesini SVG oluşturucuya ekler.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDistantLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? diffuseConstant = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDiffuseLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'feDiffuseLighting' öğesinin ekleneceği SVG oluşturucu örneği. |
| lightSource | Difüz aydınlatma etkisi için ışık kaynağını yapılandırmak amacıyla bir eylem. |
| lightingColor | Işığın rengi. İsteğe bağlı parametre. |
| surfaceScale | Aydınlatma etkisi için yüzey ölçek faktörü. İsteğe bağlı parametre. |
| diffuseConstant | Aydınlatma etkisini belirlemek için kullanılan sabit. İsteğe bağlı parametre. |
| in | Difüz aydınlatma etkisi için giriş. Bir dize ya da FilterInput olabilir. İsteğe bağlı parametre. |
| result | Bu filtre ilkel öğesi için sonuç tanımlayıcısı. İsteğe bağlı parametre. |
| x | Filtre ilkel öğesinin alt bölgesinin x koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| y | Filtre ilkel öğesinin alt bölgesinin y koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| width | Filtre ilkel öğesinin alt bölgesinin genişliği. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| yükseklik | Filtre ilkel alt bölgesinin yüksekliği. Bir double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| dolgu | Eleman için dolgu rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| çizgi | Eleman için çizgi rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| id | Filtre ilkel elemanının benzersiz tanımlayıcısı. İsteğe bağlı parametre. |
| genişlet | SVGFEDiffuseLightingElementBuilder'ı daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGFEDistantLightElementBuilder](../../svgfedistantlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEPointLightElementBuilder&gt;, Color?, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting_2}

Belirtilen bir ışık kaynağı kullanarak difüz aydınlatma etkisi uygulayan bir 'feDiffuseLighting' öğesini SVG oluşturucuya ekler.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEPointLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? diffuseConstant = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDiffuseLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'feDiffuseLighting' öğesinin ekleneceği SVG oluşturucu örneği. |
| lightSource | Difüz aydınlatma etkisi için ışık kaynağını yapılandırmak amacıyla bir eylem. |
| lightingColor | Işığın rengi. İsteğe bağlı parametre. |
| surfaceScale | Aydınlatma etkisi için yüzey ölçek faktörü. İsteğe bağlı parametre. |
| diffuseConstant | Aydınlatma etkisini belirlemek için kullanılan sabit. İsteğe bağlı parametre. |
| in | Difüz aydınlatma etkisi için giriş. Bir dize ya da FilterInput olabilir. İsteğe bağlı parametre. |
| result | Bu filtre ilkel öğesi için sonuç tanımlayıcısı. İsteğe bağlı parametre. |
| x | Filtre ilkel öğesinin alt bölgesinin x koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| y | Filtre ilkel öğesinin alt bölgesinin y koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| width | Filtre ilkel öğesinin alt bölgesinin genişliği. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| yükseklik | Filtre ilkel alt bölgesinin yüksekliği. Bir double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| dolgu | Eleman için dolgu rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| çizgi | Eleman için çizgi rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| id | Filtre ilkel elemanının benzersiz tanımlayıcısı. İsteğe bağlı parametre. |
| genişlet | SVGFEDiffuseLightingElementBuilder'ı daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGFEPointLightElementBuilder](../../svgfepointlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpotLightElementBuilder&gt;, Color?, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting_3}

Belirtilen bir ışık kaynağı kullanarak difüz aydınlatma etkisi uygulayan bir 'feDiffuseLighting' öğesini SVG oluşturucuya ekler.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpotLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? diffuseConstant = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDiffuseLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'feDiffuseLighting' öğesinin ekleneceği SVG oluşturucu örneği. |
| lightSource | Difüz aydınlatma etkisi için ışık kaynağını yapılandırmak amacıyla bir eylem. |
| lightingColor | Işığın rengi. İsteğe bağlı parametre. |
| surfaceScale | Aydınlatma etkisi için yüzey ölçek faktörü. İsteğe bağlı parametre. |
| diffuseConstant | Aydınlatma etkisini belirlemek için kullanılan sabit. İsteğe bağlı parametre. |
| in | Difüz aydınlatma etkisi için giriş. Bir dize ya da FilterInput olabilir. İsteğe bağlı parametre. |
| result | Bu filtre ilkel öğesi için sonuç tanımlayıcısı. İsteğe bağlı parametre. |
| x | Filtre ilkel öğesinin alt bölgesinin x koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| y | Filtre ilkel öğesinin alt bölgesinin y koordinatı. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| width | Filtre ilkel öğesinin alt bölgesinin genişliği. Bir double veya LengthType içeren ValueTuple olabilir. İsteğe bağlı parametre. |
| yükseklik | Filtre ilkel alt bölgesinin yüksekliği. Bir double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| dolgu | Eleman için dolgu rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| çizgi | Eleman için çizgi rengi, boya veya boya sunucusu kimliği. İsteğe bağlı parametre. |
| id | Filtre ilkel elemanının benzersiz tanımlayıcısı. İsteğe bağlı parametre. |
| genişlet | SVGFEDiffuseLightingElementBuilder'ı daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGFESpotLightElementBuilder](../../svgfespotlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
