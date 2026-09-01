---
title: "SVGStyleElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGStyleElementBuilder sınıfı. Bir SVG stil öğesi oluşturmak için bir builder sınıfıdır. Bu sınıf, CSS kurallarıyla bir SVG stil öğesinin oluşturulmasını ve yapılandırılmasını kolaylaştırır."
type: docs
weight: 1630
url: /tr/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

SVG 'style' öğesini oluşturmak için bir builder sınıfı. Bu sınıf, CSS kurallarıyla bir SVG stil öğesinin oluşturulmasını ve yapılandırılmasını kolaylaştırır.

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | Stil içeriğine bir yorum ekler. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | RuleBuilder kullanarak stil öğesine bir CSS kuralı ekler. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | Stil öğesine bir CSS kuralı ekler. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Biriktirilmiş CSS kurallarıyla SVG stil öğesini oluşturur ve belirtilen belgeye ekler. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | SVG 'style' öğesinin 'media' özniteliğini ayarlar. Bu öznitelik, stillerin amaçlandığı medyayı belirtir ve stillerin medya türüne bağlı olarak koşullu olmasını sağlar. |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | SVG 'style' öğesinin 'title' özniteliğini ayarlar. Bu öznitelik, stil öğesi için öneri niteliğinde bir başlık sağlar; erişilebilirlik ve araç ipucu metni için faydalı olabilir. |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | SVG 'style' öğesinin 'type' özniteliğini ayarlar. Bu öznitelik, öğenin içeriğinin stil sayfası dilini belirtir. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
