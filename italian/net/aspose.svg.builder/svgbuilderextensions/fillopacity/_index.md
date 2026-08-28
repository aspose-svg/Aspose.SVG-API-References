---
title: "SVGBuilderExtensions.FillOpacity"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo FillOpacity di SVGBuilderExtensions. Imposta l'attributo fill-opacity per un elemento SVG. Il valore deve essere compreso tra 0.0 totalmente trasparente e 1.0 totalmente opaco"
type: docs
weight: 820
url: /it/net/aspose.svg.builder/svgbuilderextensions/fillopacity/
---
## SVGBuilderExtensions.FillOpacity<TBuilder> method

Imposta l'attributo 'fill-opacity' per un elemento SVG. Il valore deve essere compreso tra 0.0 (completamente trasparente) e 1.0 (completamente opaco).

```csharp
public static TBuilder FillOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| opacity | Il valore di opacità da impostare. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Generata se l'opacità non è nell'intervallo valido. |

### Vedi anche

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
