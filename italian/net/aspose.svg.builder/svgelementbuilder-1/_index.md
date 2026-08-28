---
title: "Classe SVGElementBuilderT"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGElementBuilder1T. Rappresenta una classe base per la creazione di elementi SVG di tipo T."
type: docs
weight: 1160
url: /it/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

Rappresenta una classe base per la costruzione di elementi SVG di tipo *T*.

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elemento SVG di cui questo builder è responsabile nella creazione. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | Ottiene l'elenco delle configurazioni da applicare all'elemento SVG. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | Aggiunge una configurazione di attributo all'elemento SVG. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Costruisce l'elemento SVG e applica tutte le configurazioni ad esso. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | Applica le configurazioni a un elemento SVG esistente. |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | Costruisce l'elemento SVG come un SVGElement generico. |

### Vedi anche

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
