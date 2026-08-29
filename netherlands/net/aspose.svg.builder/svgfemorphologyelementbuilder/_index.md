---
title: "SVGFEMorphologyElementBuilder Class"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGFEMorphologyElementBuilder class. Builderklasse voor het maken van SVG feMorphology-elementen die worden gebruikt om morfologische bewerkingen zoals dilatatie of erosie op een invoerafbeelding toe te passen."
type: docs
weight: 1370
url: /nl/net/aspose.svg.builder/svgfemorphologyelementbuilder/
---
## SVGFEMorphologyElementBuilder class

Builder-klasse voor het maken van SVG 'feMorphology'-elementen, die worden gebruikt om morfologische bewerkingen zoals dilatatie of erosie op een invoerafbeelding toe te passen.

```csharp
public class SVGFEMorphologyElementBuilder : SVGElementBuilder<SVGFEMorphologyElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGFEMorphologyElementBuilder](svgfemorphologyelementbuilder/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfemorphologyelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Voegt een scriptconfiguratie toe aan het feMorphology-element. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEMorphologyElement](../../aspose.svg.filters/svgfemorphologyelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Operator](../../aspose.svg.builder/svgfemorphologyelementbuilder/operator/)(*[MorphologyOperator](../morphologyoperator/)*) | Stelt het 'operator'-attribuut van het feMorphology-element in, waarmee het type morfologische bewerking wordt gespecificeerd. |
| [Radius](../../aspose.svg.builder/svgfemorphologyelementbuilder/radius/)(*double, double?*) | Stelt het 'radius'-attribuut van het feMorphology-element in, waarmee de straal voor de morfologische bewerking wordt gedefinieerd. |

### Zie ook

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEMorphologyElement](../../aspose.svg.filters/svgfemorphologyelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
