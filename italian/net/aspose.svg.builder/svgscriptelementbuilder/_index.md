---
title: "Classe SVGScriptElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGScriptElementBuilder. Classe builder per costruire un elemento script SVG. L'elemento script è utilizzato per incorporare o fare riferimento a script eseguibili all'interno dei documenti SVG. Questa classe fornisce metodi per impostare vari attributi specifici dell'elemento script, come type, source e impostazioni cross-origin."
type: docs
weight: 1600
url: /it/net/aspose.svg.builder/svgscriptelementbuilder/
---
## SVGScriptElementBuilder class

Classe Builder per la costruzione di un elemento SVG 'script'. L'elemento 'script' è usato per incorporare o fare riferimento a script eseguibili nei documenti SVG. Questa classe fornisce metodi per impostare vari attributi specifici dell'elemento 'script', come tipo, sorgente e impostazioni cross-origin.

```csharp
public class SVGScriptElementBuilder : SVGElementBuilder<SVGScriptElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGScriptElementBuilder](svgscriptelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGScriptElement](../../aspose.svg/svgscriptelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Crossorigin](../../aspose.svg.builder/svgscriptelementbuilder/crossorigin/)(*string*) | Imposta l'attributo 'crossorigin' dell'elemento SVG 'script', specificando le impostazioni CORS per lo script esterno. |
| [Href](../../aspose.svg.builder/svgscriptelementbuilder/href/)(*string*) | Imposta l'attributo 'href' dell'elemento SVG 'script', specificando l'URL di un file script esterno. |
| [Type](../../aspose.svg.builder/svgscriptelementbuilder/type/)(*string*) | Imposta l'attributo 'type' dell'elemento SVG 'script', specificando il tipo di linguaggio di scripting (ad es., "text/javascript"). |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGScriptElement](../../aspose.svg/svgscriptelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
