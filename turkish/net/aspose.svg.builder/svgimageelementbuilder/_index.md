---
title: "SVGImageElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGImageElementBuilder sınıfı. SVG görüntü öğesi oluşturmak için Builder sınıfı. Bu öğe, SVG grafiklerine görüntüler yerleştirmek için kullanılır. Görüntü öğesine özgü çeşitli öznitelikleri ayarlamak ve kırpma yolları, maskeler, stiller ve betikler gibi ek yapılandırmalar eklemek için yöntemler sağlar."
type: docs
weight: 1470
url: /tr/net/aspose.svg.builder/svgimageelementbuilder/
---
## SVGImageElementBuilder class

SVG 'image' öğesini oluşturmak için Builder sınıfı. Bu öğe, SVG grafiklerine görüntüler yerleştirmek için kullanılır. 'image' öğesine özgü çeşitli öznitelikleri ayarlamak ve kırpma yolları, maskeler, stiller ve betikler gibi ek yapılandırmalar eklemek için yöntemler sağlar.

```csharp
public class SVGImageElementBuilder : SVGElementBuilder<SVGImageElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGImageElementBuilder](svgimageelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddClipPath](../../aspose.svg.builder/svgimageelementbuilder/addclippath/)(*Action&lt;SVGClipPathElementBuilder&gt;*) | SVG 'image' öğesine bir kırpma yolu yapılandırması ekler. |
| [AddMask](../../aspose.svg.builder/svgimageelementbuilder/addmask/)(*Action&lt;SVGMaskElementBuilder&gt;*) | SVG 'image' öğesine bir maske yapılandırması ekler. |
| [AddScript](../../aspose.svg.builder/svgimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG 'image' öğesine bir betik yapılandırması ekler. |
| [AddStyle](../../aspose.svg.builder/svgimageelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG 'image' öğesine bir stil yapılandırması ekler. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGImageElement](../../aspose.svg/svgimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgimageelementbuilder/href/)(*string*) | SVG 'image' öğesinin 'href' özniteliğini ayarlar, gömülecek görüntünün URL'sini belirterek. |
| [HrefBase64FromBytes](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64frombytes/)(*byte[], string*) | SVG 'image' öğesinin 'href' özniteliğini, bir görüntünün base64 kodlu baytlarıyla ayarlar. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile)(*string*) | SVG 'image' öğesinin 'href' özniteliğini, base64 kodlu bir görüntü dosyasıyla ayarlar. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile_1)(*string, string*) | SVG 'image' öğesinin 'href' özniteliğini, belirtilen MIME türüyle birlikte base64 kodlu bir görüntü dosyasıyla ayarlar. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGImageElement](../../aspose.svg/svgimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
