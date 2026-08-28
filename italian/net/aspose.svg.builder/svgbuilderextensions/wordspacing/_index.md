---
title: "SVGBuilderExtensions.WordSpacing"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo WordSpacing di SVGBuilderExtensions. Imposta l'attributo word-spacing per un elemento SVG specificando il comportamento di spaziatura tra le parole"
type: docs
weight: 2340
url: /it/net/aspose.svg.builder/svgbuilderextensions/wordspacing/
---
## WordSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#wordspacing}

Imposta l'attributo 'word-spacing' per un elemento SVG, specificando il comportamento della spaziatura tra le parole.

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| value | Il valore di spaziatura parole predefinito. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## WordSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#wordspacing_1}

Imposta l'attributo 'word-spacing' per un elemento SVG, specificando il comportamento della spaziatura tra le parole con un valore personalizzato.

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| value | Il valore di spaziatura parole. |
| tipo | Il tipo di unità per il valore di spaziatura. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
