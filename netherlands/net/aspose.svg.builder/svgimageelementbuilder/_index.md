---
title: "SVGImageElementBuilder Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGImageElementBuilder klasse. Builderklasse voor het construeren van een SVG-imagelement. Dit element wordt gebruikt om afbeeldingen in SVG-grafieken in te sluiten. Het biedt methoden om verschillende attributen specifiek voor het imagelement in te stellen en om extra configuraties toe te voegen, zoals clip‑paths, masks, stijlen en scripts"
type: docs
weight: 1470
url: /nl/net/aspose.svg.builder/svgimageelementbuilder/
---
## SVGImageElementBuilder class

Builder-klasse voor het construeren van een SVG 'image'-element. Dit element wordt gebruikt om afbeeldingen in SVG‑graphics in te sluiten. Het biedt methoden om verschillende attributen specifiek voor het 'image'-element in te stellen en om extra configuraties toe te voegen, zoals clip‑paden, maskers, stijlen en scripts.

```csharp
public class SVGImageElementBuilder : SVGElementBuilder<SVGImageElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGImageElementBuilder](svgimageelementbuilder/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddClipPath](../../aspose.svg.builder/svgimageelementbuilder/addclippath/)(*Action&lt;SVGClipPathElementBuilder&gt;*) | Voegt een clip‑path configuratie toe aan het SVG 'image' element. |
| [AddMask](../../aspose.svg.builder/svgimageelementbuilder/addmask/)(*Action&lt;SVGMaskElementBuilder&gt;*) | Voegt een mask configuratie toe aan het SVG 'image' element. |
| [AddScript](../../aspose.svg.builder/svgimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Voegt een scriptconfiguratie toe aan het SVG 'image' element. |
| [AddStyle](../../aspose.svg.builder/svgimageelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Voegt een stijlconfiguratie toe aan het SVG 'image' element. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGImageElement](../../aspose.svg/svgimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgimageelementbuilder/href/)(*string*) | Stelt het 'href' attribuut van het SVG 'image' element in, waarbij de URL van de in te sluiten afbeelding wordt gespecificeerd. |
| [HrefBase64FromBytes](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64frombytes/)(*byte[], string*) | Stelt het 'href' attribuut van het SVG 'image' element in met base64‑gecodeerde bytes van een afbeelding. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile)(*string*) | Stelt het 'href' attribuut van het SVG 'image' element in met een base64‑gecodeerd afbeeldingsbestand. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile_1)(*string, string*) | Stelt het 'href' attribuut van het SVG 'image' element in met een base64‑gecodeerd afbeeldingsbestand met een gespecificeerd MIME‑type. |

### Zie ook

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGImageElement](../../aspose.svg/svgimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
