---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo OnFocusOut di SVGBuilderExtensions. Imposta l'attributo dell'evento onfocusout per gestire gli eventi di perdita di focus sull'elemento"
type: docs
weight: 1460
url: /it/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

Imposta l'attributo evento 'onfocusout' per gestire gli eventi di focus-out sull'elemento.

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione JavaScript o lo script da eseguire quando l'elemento perde il focus, tipicamente prima dell'evento 'onblur'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

## Osservazioni

L'evento 'onfocusout' viene attivato quando un elemento sta per perdere il focus. Simile a 'onfocusin', questo evento supporta il bubbling e può essere usato anche per rilevare i cambiamenti di focus sugli elementi figli.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
