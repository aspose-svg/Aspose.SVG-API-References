---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions OnFocusIn. Imposta l'attributo dell'evento onfocusin per gestire gli eventi di focus-in sull'elemento"
type: docs
weight: 1450
url: /it/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

Imposta l'attributo evento 'onfocusin' per gestire gli eventi di focus-in sull'elemento.

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione o lo script JavaScript da eseguire quando l'elemento riceve il focus, tipicamente prima dell'evento 'onfocus'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

## Osservazioni

L'evento 'onfocusin' viene attivato quando un elemento sta per ricevere il focus. Questo evento differisce da 'onfocus' perché supporta il bubbling e può essere usato anche per rilevare cambiamenti di focus sugli elementi figli.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
