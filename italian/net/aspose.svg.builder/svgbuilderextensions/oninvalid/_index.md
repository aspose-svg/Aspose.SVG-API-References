---
title: "SVGBuilderExtensions.OnInvalid"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo OnInvalid di SVGBuilderExtensions. Imposta l'attributo dell'evento oninvalid per gestire gli eventi di invalidità sugli elementi del modulo"
type: docs
weight: 1480
url: /it/net/aspose.svg.builder/svgbuilderextensions/oninvalid/
---
## SVGBuilderExtensions.OnInvalid<TBuilder> method

Imposta l'attributo evento 'oninvalid' per gestire gli eventi non validi sugli elementi del modulo.

```csharp
public static TBuilder OnInvalid<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione JavaScript o lo script da eseguire quando il valore dell'elemento è non valido. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
