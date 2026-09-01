---
title: "SVGBuilderExtensions.AddImage"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddImage yöntemi. Oluşturucuya bir image öğesi yapılandırması ekler."
type: docs
weight: 330
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addimage/
---
## AddImage<TBuilder>(*this TBuilder, Action&lt;SVGImageElementBuilder&gt;*) {#addimage}

Yapıcıya bir 'image' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, 
    Action<SVGImageElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'image' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddImage<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, string, Action&lt;SVGImageElementBuilder&gt;*) {#addimage_1}

SVG yapıcıya bir 'image' öğesi ekler, harici bir görüntüyü SVG belgesine gömer.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, string id = null, 
    Action<SVGImageElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'image' öğesinin ekleneceği SVG oluşturucu örneği. |
| href | Harici görüntünün URL'si veya referansı. İsteğe bağlı parametre. |
| x | Görüntünün yerleştirildiği x koordinatı. Double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| y | Görüntünün yerleştirildiği y koordinatı. Double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| width | Görüntünün genişliği. Double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| yükseklik | Görüntünün yüksekliği. Double veya LengthType içeren bir ValueTuple olabilir. İsteğe bağlı parametre. |
| id | Görüntü öğesi için benzersiz tanımlayıcı. İsteğe bağlı parametre. |
| genişlet | SVGImageElementBuilder'ı daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
