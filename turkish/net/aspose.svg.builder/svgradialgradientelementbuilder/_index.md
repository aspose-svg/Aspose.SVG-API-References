---
title: "SVGRadialGradientElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGRadialGradientElementBuilder sınıfı. SVG grafiklerinde radyal bir geçiş tanımlamak için kullanılan SVG radialGradient öğesini oluşturmak için bir builder sınıfı. Bu sınıf, radialGradient öğesi içinde içeriğin oluşturulmasını sağlar ve SVG'deki radialGradient öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sunar."
type: docs
weight: 1570
url: /tr/net/aspose.svg.builder/svgradialgradientelementbuilder/
---
## SVGRadialGradientElementBuilder class

Builder class for constructing an SVG 'radialGradient' element, which is used to define a radial gradient within SVG graphics. This class enables the building of content within the 'radialGradient' element and provides methods to set various attributes specific to the 'radialGradient' element in SVG.

```csharp
public class SVGRadialGradientElementBuilder : SVGElementBuilder<SVGRadialGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGRadialGradientElementBuilder](svgradialgradientelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svgradialgradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | SVG 'radialGradient' öğesine bir animate transform yapılandırması ekler. |
| [AddScript](../../aspose.svg.builder/svgradialgradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG 'radialGradient' öğesine bir script yapılandırması ekler. |
| [AddStyle](../../aspose.svg.builder/svgradialgradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG 'radialGradient' öğesine bir stil yapılandırması ekler. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGRadialGradientElement](../../aspose.svg/svgradialgradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Cx](../../aspose.svg.builder/svgradialgradientelementbuilder/cx/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' öğesinin 'cx' özniteliğini ayarlar, geçişin merkezinin x koordinatını belirtir. |
| [Cy](../../aspose.svg.builder/svgradialgradientelementbuilder/cy/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' öğesinin 'cy' özniteliğini ayarlar, geçişin merkezinin y koordinatını belirtir. |
| [Fx](../../aspose.svg.builder/svgradialgradientelementbuilder/fx/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' öğesinin 'fx' özniteliğini ayarlar, geçişin odak noktasının x koordinatını belirtir. |
| [Fy](../../aspose.svg.builder/svgradialgradientelementbuilder/fy/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' öğesinin 'fy' özniteliğini ayarlar, gradientin odak noktasının y koordinatını belirtir. |
| [Href](../../aspose.svg.builder/svgradialgradientelementbuilder/href/)(*string*) | SVG 'radialGradient' öğesinin 'href' özniteliğini ayarlar, başka bir gradient'e referans belirtir. |
| [R](../../aspose.svg.builder/svgradialgradientelementbuilder/r/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' öğesinin 'r' özniteliğini ayarlar, gradientin yarıçapını belirtir. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGRadialGradientElement](../../aspose.svg/svgradialgradientelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IGradientStopElementBuilder](../igradientstopelementbuilder/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
