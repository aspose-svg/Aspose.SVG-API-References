---
title: "SVGBuilderExtensions.StrokeDashArray"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo StrokeDashArray di SVGBuilderExtensions. Imposta l'attributo stroke-dasharray per un elemento SVG definendo il modello di trattini e spazi usati per dipingere il tratto"
type: docs
weight: 2090
url: /it/net/aspose.svg.builder/svgbuilderextensions/strokedasharray/
---
## StrokeDashArray<TBuilder>(*this TBuilder, params double[]*) {#strokedasharray_1}

Imposta l'attributo 'stroke-dasharray' per un elemento SVG, definendo il modello di linee e spazi usati per dipingere il tratto.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, params double[] dashArray)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| dashArray | L'array delle lunghezze dei trattini. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StrokeDashArray<TBuilder>(*this TBuilder, [Dash](../../dash/)*) {#strokedasharray}

Imposta l'attributo 'stroke-dasharray' per un elemento SVG usando un modello di tratteggio predefinito.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, Dash value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| value | Il modello di tratto da impostare. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [Dash](../../dash/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
