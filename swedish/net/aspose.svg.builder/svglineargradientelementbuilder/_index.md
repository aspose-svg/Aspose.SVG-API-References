---
title: "SVGLinearGradientElementBuilder klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGLinearGradientElementBuilder klass. Byggklass för att konstruera ett SVG linearGradient-element som används för att definiera en linjär gradient inom SVG-grafik. Den möjliggör byggandet av innehåll inom linearGradient-elementet och tillhandahåller metoder för att ställa in olika attribut som är specifika för linearGradient-elementet i SVG"
type: docs
weight: 1490
url: /sv/net/aspose.svg.builder/svglineargradientelementbuilder/
---
## SVGLinearGradientElementBuilder class

Builder-klass för att konstruera ett SVG 'linearGradient'-element, som används för att definiera en linjär gradient i SVG-grafik. Det möjliggör byggandet av innehåll inom 'linearGradient'-elementet och tillhandahåller metoder för att ställa in olika attribut specifika för 'linearGradient'-elementet i SVG.

```csharp
public class SVGLinearGradientElementBuilder : SVGElementBuilder<SVGLinearGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGLinearGradientElementBuilder](svglineargradientelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svglineargradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | Lägger till en animate transform-konfiguration till SVG 'linearGradient'-elementet. |
| [AddScript](../../aspose.svg.builder/svglineargradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Lägger till en skriptkonfiguration till SVG 'linearGradient'-elementet. |
| [AddStyle](../../aspose.svg.builder/svglineargradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Lägger till en stilkonfiguration till SVG 'linearGradient'-elementet. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGLinearGradientElement](../../aspose.svg/svglineargradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svglineargradientelementbuilder/href/)(*string*) | Ställer in 'href'-attributet för SVG 'linearGradient'-elementet och specificerar en referens till en annan gradient. |
| [X1](../../aspose.svg.builder/svglineargradientelementbuilder/x1/)(*double, [LengthType](../lengthtype/)*) | Ställer in 'x1'-attributet för SVG 'linearGradient'-elementet och specificerar x-koordinaten för gradientens startpunkt. |
| [X2](../../aspose.svg.builder/svglineargradientelementbuilder/x2/)(*double, [LengthType](../lengthtype/)*) | Ställer in 'x2'-attributet för SVG 'linearGradient'-elementet och specificerar x-koordinaten för gradientens slutpunkt. |
| [Y1](../../aspose.svg.builder/svglineargradientelementbuilder/y1/)(*double, [LengthType](../lengthtype/)*) | Ställer in 'y1'-attributet för SVG 'linearGradient'-elementet och specificerar y-koordinaten för gradientens startpunkt. |
| [Y2](../../aspose.svg.builder/svglineargradientelementbuilder/y2/)(*double, [LengthType](../lengthtype/)*) | Ställer in 'y2'-attributet för SVG 'linearGradient'-elementet och specificerar y-koordinaten för gradientens slutpunkt. |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGLinearGradientElement](../../aspose.svg/svglineargradientelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IGradientStopElementBuilder](../igradientstopelementbuilder/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
