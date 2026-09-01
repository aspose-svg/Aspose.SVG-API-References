---
title: "SVGScriptElementBuilder Sınıf"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGScriptElementBuilder sınıf. SVG script öğesi oluşturmak için kullanılan Builder sınıfı. Script öğesi, SVG belgelerinde çalıştırılabilir script'leri gömmek veya referans vermek için kullanılır. Bu sınıf, script öğesine özgü type, source ve cross-origin ayarları gibi çeşitli öznitelikleri ayarlama yöntemleri sunar."
type: docs
weight: 1600
url: /tr/net/aspose.svg.builder/svgscriptelementbuilder/
---
## SVGScriptElementBuilder class

SVG 'script' öğesini oluşturmak için Builder sınıfı. 'script' öğesi, SVG belgeleri içinde çalıştırılabilir betikleri gömmek veya referans vermek için kullanılır. Bu sınıf, 'script' öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sağlar, örneğin tip, kaynak ve cross-origin ayarları.

```csharp
public class SVGScriptElementBuilder : SVGElementBuilder<SVGScriptElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGScriptElementBuilder](svgscriptelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGScriptElement](../../aspose.svg/svgscriptelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Crossorigin](../../aspose.svg.builder/svgscriptelementbuilder/crossorigin/)(*string*) | SVG 'script' öğesinin 'crossorigin' özniteliğini ayarlar, harici script için CORS ayarlarını belirtir. |
| [Href](../../aspose.svg.builder/svgscriptelementbuilder/href/)(*string*) | SVG 'script' öğesinin 'href' özniteliğini ayarlar, harici bir script dosyasının URL'sini belirtir. |
| [Type](../../aspose.svg.builder/svgscriptelementbuilder/type/)(*string*) | SVG 'script' öğesinin 'type' özniteliğini ayarlar, betik dili türünü belirtir (ör. "text/javascript"). |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGScriptElement](../../aspose.svg/svgscriptelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
