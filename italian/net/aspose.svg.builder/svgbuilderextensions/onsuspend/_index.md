---
title: "SVGBuilderExtensions.OnSuspend"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions OnSuspend. Imposta l'attributo dell'evento onsuspend per gestire gli eventi quando il caricamento dei dati multimediali è sospeso"
type: docs
weight: 1800
url: /it/net/aspose.svg.builder/svgbuilderextensions/onsuspend/
---
## SVGBuilderExtensions.OnSuspend<TBuilder> method

Imposta l'attributo evento 'onsuspend' per gestire gli eventi quando il caricamento dei dati multimediali è sospeso.

```csharp
public static TBuilder OnSuspend<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione JavaScript o lo script da eseguire quando il caricamento dei dati multimediali è sospeso. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
