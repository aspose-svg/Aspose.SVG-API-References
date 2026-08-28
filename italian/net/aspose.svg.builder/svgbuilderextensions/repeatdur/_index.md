---
title: "SVGBuilderExtensions.RepeatDur"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions RepeatDur. Imposta l'attributo repeatDur che specifica la durata totale per cui l'animazione deve ripetersi."
type: docs
weight: 1960
url: /it/net/aspose.svg.builder/svgbuilderextensions/repeatdur/
---
## RepeatDur<TBuilder>(*this TBuilder, TimeSpan*) {#repeatdur_1}

Imposta l'attributo 'repeatDur', specificando la durata totale per cui l'animazione deve ripetersi.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| durata | La durata totale per ripetere l'animazione. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatDur<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatdur}

Imposta l'attributo 'repeatDur', specificando una durata totale indefinita per l'animazione usando un enum predefinito.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La durata totale indefinita predefinita per ripetere l'animazione. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
