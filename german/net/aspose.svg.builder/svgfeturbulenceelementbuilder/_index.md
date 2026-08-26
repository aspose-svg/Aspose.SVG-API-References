---
title: "SVGFETurbulenceElementBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGFETurbulenceElementBuilder Klasse. Builder-Klasse zum Erstellen von SVG feTurbulence-Elementen, die ein Bild mithilfe der Perlin-Turbulenzfunktion erzeugen."
type: docs
weight: 1430
url: /de/net/aspose.svg.builder/svgfeturbulenceelementbuilder/
---
## SVGFETurbulenceElementBuilder class

Builder-Klasse zum Erstellen von SVG‑'feTurbulence'-Elementen, die ein Bild mithilfe der Perlin‑Turbulenzfunktion erzeugen.

```csharp
public class SVGFETurbulenceElementBuilder : SVGElementBuilder<SVGFETurbulenceElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGFETurbulenceElementBuilder](svgfeturbulenceelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfeturbulenceelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Fügt dem feTurbulence-Element eine Skriptkonfiguration hinzu. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| [BaseFrequency](../../aspose.svg.builder/svgfeturbulenceelementbuilder/basefrequency/)(*double, double?*) | Setzt die Basisfrequenz für die Turbulenzfunktion. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFETurbulenceElement](../../aspose.svg.filters/svgfeturbulenceelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [NumOctaves](../../aspose.svg.builder/svgfeturbulenceelementbuilder/numoctaves/)(*int*) | Setzt die Anzahl der Oktaven für die Turbulenzfunktion. |
| [Seed](../../aspose.svg.builder/svgfeturbulenceelementbuilder/seed/)(*double*) | Setzt den Seed für den Zufallszahlengenerator, der von der Turbulenzfunktion verwendet wird. |
| [StitchTiles](../../aspose.svg.builder/svgfeturbulenceelementbuilder/stitchtiles/)(*[StitchTiles](../stitchtiles/)*) | Setzt die Option 'stitch tiles' für die Turbulenzfunktion. |
| [Type](../../aspose.svg.builder/svgfeturbulenceelementbuilder/type/)(*[TurbulenceType](../turbulencetype/)*) | Setzt den Typ der Turbulenz (fraktales Rauschen oder Turbulenz). |

### Siehe auch

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFETurbulenceElement](../../aspose.svg.filters/svgfeturbulenceelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
