---
title: "SVGRadialGradientElementBuilder-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGRadialGradientElementBuilder-klass. En byggarklass för att konstruera ett SVG radialGradient-element som används för att definiera en radialgradient i SVG-grafik. Denna klass möjliggör byggandet av innehåll inom radialGradient-elementet och tillhandahåller metoder för att sätta olika attribut specifika för radialGradient-elementet i SVG."
type: docs
weight: 1570
url: /sv/net/aspose.svg.builder/svgradialgradientelementbuilder/
---
## SVGRadialGradientElementBuilder class

Builder-klass för att konstruera ett SVG 'radialGradient'-element, som används för att definiera en radiell gradient inom SVG-grafik. Denna klass möjliggör byggandet av innehåll inom 'radialGradient'-elementet och tillhandahåller metoder för att ange olika attribut som är specifika för 'radialGradient'-elementet i SVG.

```csharp
public class SVGRadialGradientElementBuilder : SVGElementBuilder<SVGRadialGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGRadialGradientElementBuilder](svgradialgradientelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svgradialgradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | Lägger till en animate‑transform‑konfiguration till SVG‑elementet 'radialGradient'. |
| [AddScript](../../aspose.svg.builder/svgradialgradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Lägger till en skriptkonfiguration till SVG‑elementet 'radialGradient'. |
| [AddStyle](../../aspose.svg.builder/svgradialgradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Lägger till en stilkonfiguration till SVG‑elementet 'radialGradient'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGRadialGradientElement](../../aspose.svg/svgradialgradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Cx](../../aspose.svg.builder/svgradialgradientelementbuilder/cx/)(*double, [LengthType](../lengthtype/)*) | Sätter attributet 'cx' för SVG‑elementet 'radialGradient', vilket anger x‑koordinaten för gradientens centrum. |
| [Cy](../../aspose.svg.builder/svgradialgradientelementbuilder/cy/)(*double, [LengthType](../lengthtype/)*) | Sätter attributet 'cy' för SVG‑elementet 'radialGradient', vilket anger y‑koordinaten för gradientens centrum. |
| [Fx](../../aspose.svg.builder/svgradialgradientelementbuilder/fx/)(*double, [LengthType](../lengthtype/)*) | Ställer in 'fx'-attributet för SVG-elementet 'radialGradient' och anger x-koordinaten för gradientens fokalpunkt. |
| [Fy](../../aspose.svg.builder/svgradialgradientelementbuilder/fy/)(*double, [LengthType](../lengthtype/)*) | Ställer in 'fy'-attributet för SVG-elementet 'radialGradient' och anger y-koordinaten för gradientens fokalpunkt. |
| [Href](../../aspose.svg.builder/svgradialgradientelementbuilder/href/)(*string*) | Ställer in 'href'-attributet för SVG-elementet 'radialGradient' och anger en referens till en annan gradient. |
| [R](../../aspose.svg.builder/svgradialgradientelementbuilder/r/)(*double, [LengthType](../lengthtype/)*) | Ställer in 'r'-attributet för SVG-elementet 'radialGradient' och anger gradientens radie. |

### Se även

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
