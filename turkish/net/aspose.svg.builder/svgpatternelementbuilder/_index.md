---
title: "SVGPatternElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGPatternElementBuilder sınıfı. SVG içinde grafik öğelerini doldurmak için kullanılacak bir deseni tanımlamak amacıyla bir SVG pattern öğesi oluşturmak için kullanılan Builder sınıfı. Bu sınıf, pattern öğesine özgü çeşitli öznitelikleri ayarlamak ve içeriğini oluşturmak için yöntemler sağlar."
type: docs
weight: 1540
url: /tr/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

SVG 'pattern' öğesini oluşturmak için Builder sınıfı, bu öğe SVG içinde grafik öğelerini doldurmak için kullanılacak bir desen tanımlamakta kullanılır. Bu sınıf 'pattern' öğesine özgü çeşitli öznitelikleri ayarlamak ve içeriğini oluşturmak için yöntemler sağlar.

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | SVG 'pattern' öğesinin 'href' özniteliğini ayarlar, bu pattern'in özelliklerini devraldığı başka bir pattern'e referans belirtir. |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'pattern' öğesinin 'patternContentUnits' özniteliğini ayarlar, pattern içeriğinin koordinat sistemini belirtir. |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | SVG 'pattern' öğesinin 'patternTransform' özniteliğini ayarlar, pattern'e bir dönüşüm uygular. |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'pattern' öğesinin 'patternUnits' özniteliğini ayarlar, pattern'in x, y, genişlik ve yükseklik koordinat sistemini belirtir. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPatternElement](../../aspose.svg/svgpatternelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
