---
title: "SVGBuilderExtensions.OnError"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo OnError di SVGBuilderExtensions. Imposta l'attributo dell'evento onerror per gestire gli eventi di errore sull'elemento"
type: docs
weight: 1430
url: /it/net/aspose.svg.builder/svgbuilderextensions/onerror/
---
## SVGBuilderExtensions.OnError<TBuilder> method

Imposta l'attributo evento 'onerror' per gestire gli eventi di errore sull'elemento.

```csharp
public static TBuilder OnError<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, ICommonEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione JavaScript o lo script da eseguire quando si verifica un errore. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICommonEventAttributeSetter](../../icommoneventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
