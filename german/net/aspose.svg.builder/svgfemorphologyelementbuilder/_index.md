---
title: "SVGFEMorphologyElementBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGFEMorphologyElementBuilder Klasse. Builder‑Klasse zum Erstellen von SVG‑feMorphology‑Elementen, die verwendet werden, um morphologische Operationen wie Dilatation oder Erosion auf ein Eingabebild anzuwenden."
type: docs
weight: 1370
url: /de/net/aspose.svg.builder/svgfemorphologyelementbuilder/
---
## SVGFEMorphologyElementBuilder class

Builder-Klasse zum Erstellen von SVG‑'feMorphology'-Elementen, die morphologische Operationen wie Dilatation oder Erosion auf ein Eingabebild anwenden.

```csharp
public class SVGFEMorphologyElementBuilder : SVGElementBuilder<SVGFEMorphologyElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGFEMorphologyElementBuilder](svgfemorphologyelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfemorphologyelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Fügt dem feMorphology‑Element eine Skriptkonfiguration hinzu. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEMorphologyElement](../../aspose.svg.filters/svgfemorphologyelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Operator](../../aspose.svg.builder/svgfemorphologyelementbuilder/operator/)(*[MorphologyOperator](../morphologyoperator/)*) | Setzt das Attribut 'operator' des feMorphology‑Elements und gibt den Typ der morphologischen Operation an. |
| [Radius](../../aspose.svg.builder/svgfemorphologyelementbuilder/radius/)(*double, double?*) | Setzt das Attribut 'radius' des feMorphology‑Elements und definiert den Radius für die morphologische Operation. |

### Siehe auch

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEMorphologyElement](../../aspose.svg.filters/svgfemorphologyelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
