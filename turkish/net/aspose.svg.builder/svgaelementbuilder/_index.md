---
title: "SVGAElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGAElementBuilder sınıfı. Hipermetin bağlantılarını tanımlamak için kullanılan bir SVG a öğesini oluşturmak için Builder sınıfı. Bir öğe içinde içeriğin oluşturulmasını sağlar ve SVG'deki a öğesine özgü çeşitli öznitelikleri ayarlama yöntemleri sunar."
type: docs
weight: 1070
url: /tr/net/aspose.svg.builder/svgaelementbuilder/
---
## SVGAElementBuilder class

SVG 'a' öğesini (hiperlink tanımlamak için kullanılan) oluşturmak için bir oluşturucu sınıfı. 'a' öğesi içinde içerik oluşturmayı sağlar ve SVG'deki 'a' öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sunar.

```csharp
public class SVGAElementBuilder : SVGElementBuilder<SVGAElement>, ICompositeAttributeSetter, 
    ICompositeElementBuilder
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGAElementBuilder](svgaelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGAElement](../../aspose.svg/svgaelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Download](../../aspose.svg.builder/svgaelementbuilder/download/)(*string*) | SVG 'a' öğesinin 'download' özniteliğini ayarlar, bağlantının etkinleştirildiğinde indirilmesi gerektiğini gösterir. |
| [Href](../../aspose.svg.builder/svgaelementbuilder/href/)(*string*) | SVG 'a' öğesinin 'href' özniteliğini ayarlar, bağlanan kaynağın URL'sini belirtir. |
| [HrefLang](../../aspose.svg.builder/svgaelementbuilder/hreflang/)(*string*) | SVG 'a' öğesinin 'hreflang' özniteliğini ayarlar, bağlanan kaynağın dilini gösterir. |
| [Ping](../../aspose.svg.builder/svgaelementbuilder/ping/)(*string*) | SVG 'a' öğesinin 'ping' özniteliğini ayarlar, bağlantı izlenirse bildirilecek URL listesini içerir. |
| [ReferrerPolicy](../../aspose.svg.builder/svgaelementbuilder/referrerpolicy/)(*[ReferrerPolicy](../referrerpolicy/)*) | SVG 'a' öğesinin 'referrerPolicy' özniteliğini ayarlar, isteklerle birlikte gönderilecek referans bilgisinin miktarını belirler. |
| [Rel](../../aspose.svg.builder/svgaelementbuilder/rel/)(*string*) | SVG 'a' öğesinin 'rel' özniteliğini ayarlar, hedef nesnenin bağlantı nesnesine olan ilişkisini belirtir. |
| [SetTarget](../../aspose.svg.builder/svgaelementbuilder/settarget/)(*string*) | SVG 'a' öğesinin 'target' özniteliğini özel bir XML adıyla ayarlar. |
| [Type](../../aspose.svg.builder/svgaelementbuilder/type/)(*string*) | SVG 'a' öğesinin 'type' özniteliğini ayarlar, bağlanan kaynağın medya tipini belirtir. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGAElement](../../aspose.svg/svgaelement/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
