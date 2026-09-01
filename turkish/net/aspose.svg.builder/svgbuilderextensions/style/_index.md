---
title: "SVGBuilderExtensions.Style"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGBuilderExtensions Style yöntemi. CSS stillerini tanımlamak için bir kural oluşturucu kullanarak style özniteliğini ayarlar"
type: docs
weight: 2160
url: /tr/net/aspose.svg.builder/svgbuilderextensions/style/
---
## Style<TBuilder>(*this TBuilder, Action&lt;RuleBuilder&gt;*) {#style}

CSS stillerini tanımlamak için bir kural oluşturucu kullanarak 'style' özniteliğini ayarlar.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, Action<RuleBuilder> configureRule)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| configureRule | CSS kuralını yapılandırmak için eylem. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* class [RuleBuilder](../../rulebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Style<TBuilder>(*this TBuilder, string*) {#style_1}

SVG öğesi için satır içi CSS stillerini tanımlayan 'style' özniteliğini ayarlar.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, string rules)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Parametre | Açıklama |
| --- | --- |
| TBuilder | SVG öğe oluşturucusunun türü. |
| oluşturucu | SVG öğe oluşturucu. |
| rules | CSS kuralları bir dize olarak. |

### Dönüş Değeri

Zincirleme için oluşturucu örneği.

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
