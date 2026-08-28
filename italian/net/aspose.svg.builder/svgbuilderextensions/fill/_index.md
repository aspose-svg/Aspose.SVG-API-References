---
title: "SVGBuilderExtensions.Fill"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo Fill di SVGBuilderExtensions. Imposta l'attributo fill definendo come l'animazione dovrebbe applicare gli stili al di fuori della sua durata attiva."
type: docs
weight: 810
url: /it/net/aspose.svg.builder/svgbuilderextensions/fill/
---
## Fill<TBuilder>(*this TBuilder, [AnimationFill](../../animationfill/)*) {#fill}

Imposta l'attributo 'fill', definendo come l'animazione dovrebbe applicare gli stili al di fuori della sua durata attiva.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, AnimationFill value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | Il comportamento di riempimento dell'animazione. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [AnimationFill](../../animationfill/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, Action&lt;PaintBuilder&gt;*) {#fill_2}

Imposta l'attributo 'fill' per un elemento SVG utilizzando una configurazione personalizzata.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Action<PaintBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | Un delegato per configurare il PaintBuilder. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [PaintBuilder](../../paintbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, Color*) {#fill_3}

Imposta l'attributo 'fill' per un elemento SVG utilizzando un colore.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Color color)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| colore | Il colore da impostare come riempimento. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, [Paint](../../paint/)*) {#fill_1}

Imposta l'attributo 'fill' per un elemento SVG utilizzando un valore enum Paint predefinito.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Paint paint)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| paint | Il valore enum Paint da impostare. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [Paint](../../paint/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
