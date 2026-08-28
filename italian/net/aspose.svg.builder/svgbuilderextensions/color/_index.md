---
title: "SVGBuilderExtensions.Color"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions Color. Imposta l'attributo color per un elemento SVG utilizzando una configurazione personalizzata."
type: docs
weight: 670
url: /it/net/aspose.svg.builder/svgbuilderextensions/color/
---
## Color<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#color}

Imposta l'attributo 'color' per un elemento SVG usando una configurazione personalizzata.

```csharp
public static TBuilder Color<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | Un delegato per configurare il colore. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Color<TBuilder>(*this TBuilder, Color*) {#color_1}

Imposta l'attributo 'color' per un elemento SVG usando un valore di colore.

```csharp
public static TBuilder Color<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| colorValue | Il valore del colore da impostare. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
