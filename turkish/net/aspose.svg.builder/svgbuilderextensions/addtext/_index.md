---
title: "SVGBuilderExtensions.AddText"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddText yöntemi. Bir metin öğesi yapılandırmasını oluşturucuya ekler"
type: docs
weight: 530
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

Derleyiciye bir 'text' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'text' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

SVG derleyicisine belirtilen içerik ve özniteliklere sahip bir 'text' öğesi ekler.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Zincirleme olanağı sağlayan SVG öğe oluşturucusunun tipi. |
| oluşturucu | 'text' öğesinin ekleneceği oluşturucu örneği. |
| content | 'text' öğesi içinde gösterilecek metin içeriği. |
| x | Metin öğesi için x-koordinatı. Çift (double) bir değer veya çift ve LengthType ikilisi olabilir. |
| y | Metin öğesi için y-koordinatı. Çift (double) bir değer veya çift ve LengthType ikilisi olabilir. |
| fontSize | Metin için yazı tipi boyutu. Çift (double) bir değer veya çift ve LengthType ikilisi olabilir. |
| fontStyle | Metin için yazı tipi stili (ör. normal, italic, oblique). |
| fontFamily | Metin için yazı tipi ailesi (ör. Arial, Verdana). |
| fontWeight | Yazı tipinin ağırlığı (kalınlığı) (ör. normal, bold). |
| dolgu | Metin için doldurma rengi veya boya stili. Bir Color, Paint enum değeri veya paint server kimliği olabilir. |
| çizgi | Metin için çizgi rengi veya boya stili. Bir Color, Paint enum değeri veya paint server kimliği olabilir. |
| id | Metin öğesi için benzersiz tanımlayıcı. |
| genişlet | Metin öğesi oluşturucusunu daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Daha fazla ekleme veya yapılandırma zincirlemek için oluşturucu örneği.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
