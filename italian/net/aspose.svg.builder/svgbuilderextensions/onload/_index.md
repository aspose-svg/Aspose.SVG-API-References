---
title: "SVGBuilderExtensions.OnLoad"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions OnLoad. Imposta l'attributo dell'evento onload per gestire gli eventi di caricamento sull'elemento"
type: docs
weight: 1520
url: /it/net/aspose.svg.builder/svgbuilderextensions/onload/
---
## SVGBuilderExtensions.OnLoad<TBuilder> method

Imposta l'attributo evento 'onload' per gestire gli eventi di caricamento sull'elemento.

```csharp
public static TBuilder OnLoad<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione JavaScript o lo script da eseguire quando l'elemento ha terminato il caricamento. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
