---
title: "SVGBuilderExtensions.Min"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions Min. Imposta l'attributo min specificando la durata minima dell'animazione"
type: docs
weight: 1170
url: /it/net/aspose.svg.builder/svgbuilderextensions/min/
---
## Min<TBuilder>(*this TBuilder, TimeSpan*) {#min_1}

Imposta l'attributo 'min', specificando la durata minima dell'animazione.

```csharp
public static TBuilder Min<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| durata | La durata minima dell'animazione. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Min<TBuilder>(*this TBuilder, [Media](../../media/)*) {#min}

Imposta l'attributo 'min', specificando la condizione di durata minima per l'animazione basata sui media.

```csharp
public static TBuilder Min<TBuilder>(this TBuilder builder, Media value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La condizione di durata minima relativa ai media per l'animazione. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [Media](../../media/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
