---
title: "SVGBuilderExtensions.AddPath"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions AddPath yöntemi. Oluşturucuya bir path öğesi yapılandırması ekler"
type: docs
weight: 400
url: /tr/net/aspose.svg.builder/svgbuilderextensions/addpath/
---
## AddPath<TBuilder>(*this TBuilder, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_2}

Yapıcıya bir 'path' öğesi yapılandırması ekler.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    Action<SVGPathElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | Oluşturucu örneği. |
| yapılandır | 'path' öğesi için yapılandırma eylemi. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, OneOf&lt;string, Action&lt;PathBuilder&gt;&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath}

SVG yapıcıya bir 'path' öğesi ekler, yol verisini ve stillerini belirtir.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    OneOf<string, Action<PathBuilder>> d, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'path' öğesinin ekleneceği SVG oluşturucu örneği. |
| d | Yol verilerini temsil eden bir dize olabilen veya bir PathBuilder'ı yapılandıran bir eylem olabilen OneOf türü. |
| dolgu | Yolun doldurma rengi veya boya stili. Bir Color veya Paint enum değeri ya da boya sunucusu kimliği olabilir. İsteğe bağlı parametre. |
| çizgi | Yolun kontur rengi veya boya stili. Bir Color veya Paint enum değeri ya da boya sunucusu kimliği olabilir. İsteğe bağlı parametre. |
| id | Path öğesi için benzersiz tanımlayıcı. İsteğe bağlı parametre. |
| genişlet | Path öğesi oluşturucusunu daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, Action&lt;PathBuilder&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_1}

PathBuilder'ı doğrudan yapılandırmak için bir eylem alan AddPath aşırı yüklemesi.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, Action<PathBuilder> d, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | Fluent API kullanımını kolaylaştıran SVG öğe oluşturucusunun türü. |
| oluşturucu | 'path' öğesinin ekleneceği SVG oluşturucu örneği. |
| d | Path verilerini tanımlamak için bir PathBuilder'ı yapılandıran bir eylem. |
| dolgu | Yolun doldurma rengi veya boya stili. Bir Color veya Paint enum değeri ya da boya sunucusu kimliği olabilir. İsteğe bağlı parametre. |
| çizgi | Yolun kontur rengi veya boya stili. Bir Color veya Paint enum değeri ya da boya sunucusu kimliği olabilir. İsteğe bağlı parametre. |
| id | Path öğesi için benzersiz tanımlayıcı. İsteğe bağlı parametre. |
| genişlet | Path öğesi oluşturucusunu daha da yapılandırmak için isteğe bağlı bir eylem. |

### Dönüş Değeri

Metot zincirlemesine izin veren oluşturucu örneği.

### Ayrıca Bakınız

* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
