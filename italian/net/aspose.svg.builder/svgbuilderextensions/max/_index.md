---
title: "SVGBuilderExtensions.Max"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo Max di SVGBuilderExtensions. Imposta l'attributo max che specifica la durata massima dell'animazione."
type: docs
weight: 1160
url: /it/net/aspose.svg.builder/svgbuilderextensions/max/
---
## Max<TBuilder>(*this TBuilder, TimeSpan*) {#max_1}

Imposta l'attributo 'max', specificando la durata massima dell'animazione.

```csharp
public static TBuilder Max<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| durata | La durata massima dell'animazione. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Max<TBuilder>(*this TBuilder, [Media](../../media/)*) {#max}

Imposta l'attributo 'max', specificando la condizione di durata massima predefinita per l'animazione.

```csharp
public static TBuilder Max<TBuilder>(this TBuilder builder, Media value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La condizione di durata massima predefinita per l'animazione. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [Media](../../media/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
