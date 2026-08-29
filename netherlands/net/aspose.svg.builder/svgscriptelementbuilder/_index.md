---
title: "SVGScriptElementBuilder Class"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGScriptElementBuilder class. Builder‑klasse voor het construeren van een SVG‑scriptelement. Het scriptelement wordt gebruikt om uitvoerbare scripts in SVG‑documenten in te sluiten of te refereren. Deze klasse biedt methoden om verschillende attributen specifiek voor het scriptelement in te stellen, zoals type, source en cross‑origin‑instellingen."
type: docs
weight: 1600
url: /nl/net/aspose.svg.builder/svgscriptelementbuilder/
---
## SVGScriptElementBuilder class

Builder-klasse voor het construeren van een SVG 'script'-element. Het 'script'-element wordt gebruikt om uitvoerbare scripts in SVG-documenten in te sluiten of te refereren. Deze klasse biedt methoden om verschillende attributen specifiek voor het 'script'-element in te stellen, zoals type, bron en cross-origin-instellingen.

```csharp
public class SVGScriptElementBuilder : SVGElementBuilder<SVGScriptElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGScriptElementBuilder](svgscriptelementbuilder/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGScriptElement](../../aspose.svg/svgscriptelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Crossorigin](../../aspose.svg.builder/svgscriptelementbuilder/crossorigin/)(*string*) | Stelt het 'crossorigin'-attribuut van het SVG 'script'-element in, waarmee de CORS‑instellingen voor het externe script worden gespecificeerd. |
| [Href](../../aspose.svg.builder/svgscriptelementbuilder/href/)(*string*) | Stelt het 'href'-attribuut van het SVG 'script'-element in, waarmee de URL van een extern scriptbestand wordt gespecificeerd. |
| [Type](../../aspose.svg.builder/svgscriptelementbuilder/type/)(*string*) | Stelt het 'type'-attribuut van het SVG 'script'-element in, waarmee het type scripttaal wordt gespecificeerd (bijv. "text/javascript"). |

### Zie ook

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGScriptElement](../../aspose.svg/svgscriptelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
