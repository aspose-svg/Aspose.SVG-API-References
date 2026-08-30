---
title: "SVGFETurbulenceElementBuilder Class"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGFETurbulenceElementBuilder class. Byggklass för att skapa SVG feTurbulence-element som genererar en bild med Perlin-turbulensfunktionen."
type: docs
weight: 1430
url: /sv/net/aspose.svg.builder/svgfeturbulenceelementbuilder/
---
## SVGFETurbulenceElementBuilder class

Builder-klass för att skapa SVG 'feTurbulence'-element, som skapar en bild med hjälp av Perlin-turbulensfunktionen.

```csharp
public class SVGFETurbulenceElementBuilder : SVGElementBuilder<SVGFETurbulenceElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGFETurbulenceElementBuilder](svgfeturbulenceelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfeturbulenceelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Lägger till en skriptkonfiguration till feTurbulence-elementet. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| [BaseFrequency](../../aspose.svg.builder/svgfeturbulenceelementbuilder/basefrequency/)(*double, double?*) | Ställer in basfrekvensen för turbulensfunktionen. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFETurbulenceElement](../../aspose.svg.filters/svgfeturbulenceelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [NumOctaves](../../aspose.svg.builder/svgfeturbulenceelementbuilder/numoctaves/)(*int*) | Ställer in antalet oktaver för turbulensfunktionen. |
| [Seed](../../aspose.svg.builder/svgfeturbulenceelementbuilder/seed/)(*double*) | Ställer in fröet för slumpgeneratorn som används av turbulensfunktionen. |
| [StitchTiles](../../aspose.svg.builder/svgfeturbulenceelementbuilder/stitchtiles/)(*[StitchTiles](../stitchtiles/)*) | Ställer in alternativet för sömnad av plattor för turbulensfunktionen. |
| [Type](../../aspose.svg.builder/svgfeturbulenceelementbuilder/type/)(*[TurbulenceType](../turbulencetype/)*) | Ställer in typen av turbulens (fraktalbrus eller turbulens). |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFETurbulenceElement](../../aspose.svg.filters/svgfeturbulenceelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
