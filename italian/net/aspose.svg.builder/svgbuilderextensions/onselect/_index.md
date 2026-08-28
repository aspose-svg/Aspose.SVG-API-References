---
title: "SVGBuilderExtensions.OnSelect"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo OnSelect di SVGBuilderExtensions. Imposta l'attributo dell'evento onselect per gestire gli eventi di selezione del testo sull'elemento"
type: docs
weight: 1760
url: /it/net/aspose.svg.builder/svgbuilderextensions/onselect/
---
## SVGBuilderExtensions.OnSelect<TBuilder> method

Imposta l'attributo evento 'onselect' per gestire gli eventi di selezione del testo sull'elemento.

```csharp
public static TBuilder OnSelect<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione o lo script JavaScript da eseguire quando il testo è selezionato all'interno dell'elemento. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
