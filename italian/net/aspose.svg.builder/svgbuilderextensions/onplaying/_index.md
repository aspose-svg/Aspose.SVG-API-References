---
title: "SVGBuilderExtensions.OnPlaying"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions OnPlaying. Imposta l'attributo dell'evento onplaying per gestire gli eventi quando il media è attivamente in riproduzione dopo essere stato messo in pausa o fermato per il buffering."
type: docs
weight: 1670
url: /it/net/aspose.svg.builder/svgbuilderextensions/onplaying/
---
## SVGBuilderExtensions.OnPlaying<TBuilder> method

Imposta l'attributo evento 'onplaying' per gestire gli eventi quando il media è in riproduzione attiva dopo essere stato messo in pausa o fermato per il buffering.

```csharp
public static TBuilder OnPlaying<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione JavaScript o lo script da eseguire quando il media è attivamente in riproduzione. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
