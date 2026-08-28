---
title: "SVGBuilderExtensions.OnUnload"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo OnUnload di SVGBuilderExtensions. Imposta l'attributo evento onunload definendo uno script da eseguire quando il documento SVG viene scaricato"
type: docs
weight: 1830
url: /it/net/aspose.svg.builder/svgbuilderextensions/onunload/
---
## SVGBuilderExtensions.OnUnload<TBuilder> method

Imposta l'attributo evento 'onunload', definendo uno script da eseguire quando il documento SVG viene scaricato.

```csharp
public static TBuilder OnUnload<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione JavaScript o lo script da eseguire quando il documento viene scaricato. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
