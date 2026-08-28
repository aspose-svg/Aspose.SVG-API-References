---
title: "SVGBuilderExtensions.OnDrop"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo OnDrop di SVGBuilderExtensions. Imposta l'attributo dell'evento ondrop per gestire il rilascio di un elemento su un target di drop valido."
type: docs
weight: 1380
url: /it/net/aspose.svg.builder/svgbuilderextensions/ondrop/
---
## SVGBuilderExtensions.OnDrop<TBuilder> method

Imposta l'attributo evento 'ondrop' per gestire il rilascio di un elemento su un target di rilascio valido.

```csharp
public static TBuilder OnDrop<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione JavaScript o lo script da eseguire quando un elemento viene rilasciato su un target di drop valido. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
