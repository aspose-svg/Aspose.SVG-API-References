---
title: "SVGBuilderExtensions.OnProgress"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions OnProgress. Imposta l'attributo dell'evento onprogress per gestire gli eventi che indicano l'avanzamento di un processo in corso."
type: docs
weight: 1680
url: /it/net/aspose.svg.builder/svgbuilderextensions/onprogress/
---
## SVGBuilderExtensions.OnProgress<TBuilder> method

Imposta l'attributo evento 'onprogress' per gestire gli eventi che indicano l'avanzamento di un processo in corso.

```csharp
public static TBuilder OnProgress<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione o lo script JavaScript da eseguire per indicare l'avanzamento di un processo in corso. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
