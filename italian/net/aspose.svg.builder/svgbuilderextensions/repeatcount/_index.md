---
title: "SVGBuilderExtensions.RepeatCount"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions RepeatCount. Imposta l'attributo repeatCount definendo quante volte l'animazione deve ripetersi"
type: docs
weight: 1950
url: /it/net/aspose.svg.builder/svgbuilderextensions/repeatcount/
---
## RepeatCount<TBuilder>(*this TBuilder, int*) {#repeatcount_1}

Imposta l'attributo 'repeatCount', definendo quante volte l'animazione deve ripetersi.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, int value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | Il numero di volte in cui l'animazione deve ripetersi. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatCount<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatcount}

Imposta l'attributo 'repeatCount', definendo un conteggio di ripetizione indefinito per l'animazione usando un enum predefinito.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | Il conteggio di ripetizione indefinito predefinito per l'animazione. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
