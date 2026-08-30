---
title: "SVGScriptElementBuilder klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGScriptElementBuilder klass. Byggklass för att konstruera ett SVG‑script‑element. Script‑elementet används för att bädda in eller referera till körbara skript i SVG‑dokument. Denna klass tillhandahåller metoder för att ställa in olika attribut som är specifika för script‑elementet, såsom typ, källa och cross‑origin‑inställningar."
type: docs
weight: 1600
url: /sv/net/aspose.svg.builder/svgscriptelementbuilder/
---
## SVGScriptElementBuilder class

Builder-klass för att konstruera ett SVG 'script'-element. 'Script'-elementet används för att bädda in eller referera körbara skript inom SVG-dokument. Denna klass tillhandahåller metoder för att ange olika attribut som är specifika för 'script'-elementet, såsom typ, källa och cross-origin-inställningar.

```csharp
public class SVGScriptElementBuilder : SVGElementBuilder<SVGScriptElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGScriptElementBuilder](svgscriptelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGScriptElement](../../aspose.svg/svgscriptelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Crossorigin](../../aspose.svg.builder/svgscriptelementbuilder/crossorigin/)(*string*) | Ställer in attributet 'crossorigin' för SVG‑'script'‑elementet och specificerar CORS‑inställningarna för det externa skriptet. |
| [Href](../../aspose.svg.builder/svgscriptelementbuilder/href/)(*string*) | Ställer in attributet 'href' för SVG‑'script'‑elementet och specificerar URL:en för en extern skriptfil. |
| [Type](../../aspose.svg.builder/svgscriptelementbuilder/type/)(*string*) | Ställer in attributet 'type' för SVG‑'script'‑elementet och specificerar typen av skriptspråk (t.ex. "text/javascript"). |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGScriptElement](../../aspose.svg/svgscriptelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
