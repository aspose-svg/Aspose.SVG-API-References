---
title: "Classe SVGStyleElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGStyleElementBuilder. Una classe builder per costruire un elemento di stile SVG. Questa classe facilita la creazione e la configurazione di un elemento di stile SVG con regole CSS"
type: docs
weight: 1630
url: /it/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

Una classe builder per la costruzione di un elemento SVG 'style'. Questa classe facilita la creazione e la configurazione di un elemento di stile SVG con regole CSS.

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | Aggiunge un commento al contenuto dello stile. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | Aggiunge una regola CSS all'elemento di stile utilizzando un RuleBuilder. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | Aggiunge una regola CSS all'elemento di stile. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Costruisce l'elemento di stile SVG con le regole CSS accumulate e lo aggiunge al documento specificato. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | Imposta l'attributo 'media' dell'elemento SVG 'style'. Questo attributo specifica i media per i quali gli stili sono destinati, consentendo che gli stili siano condizionali al tipo di media. |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | Imposta l'attributo 'title' dell'elemento SVG 'style'. Questo attributo fornisce un titolo consigliato per l'elemento style, che può essere utile per l'accessibilità e il testo dei suggerimenti. |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | Imposta l'attributo 'type' dell'elemento SVG 'style'. Questo attributo specifica il linguaggio del foglio di stile del contenuto dell'elemento. |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
