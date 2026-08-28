---
title: "SVGBuilderExtensions.StopColor"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo StopColor di SVGBuilderExtensions. Imposta l'attributo stop-color per un elemento SVG che definisce il colore a una fermata del gradiente"
type: docs
weight: 2060
url: /it/net/aspose.svg.builder/svgbuilderextensions/stopcolor/
---
## StopColor<TBuilder>(*this TBuilder, Color*) {#stopcolor_1}

Imposta l'attributo 'stop-color' per un elemento SVG, definendo il colore a una fermata del gradiente.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Color colorValue)
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

---

## StopColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#stopcolor}

Imposta l'attributo 'stop-color' per un elemento SVG usando una configurazione di colore personalizzata.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
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
