---
title: "SVGBuilderExtensions.BaselineShift"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo BaselineShift di SVGBuilderExtensions. Imposta l'attributo baseline-shift per un elemento SVG usando un valore predefinito."
type: docs
weight: 600
url: /it/net/aspose.svg.builder/svgbuilderextensions/baselineshift/
---
## BaselineShift<TBuilder>(*this TBuilder, [BaseLineShift](../../baselineshift/)*) {#baselineshift}

Imposta l'attributo 'baseline-shift' per un elemento SVG usando un valore predefinito.

```csharp
public static TBuilder BaselineShift<TBuilder>(this TBuilder builder, BaseLineShift value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| value | Il valore di baseline shift da impostare. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [BaseLineShift](../../baselineshift/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## BaselineShift<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#baselineshift_1}

Imposta l'attributo 'baseline-shift' per un elemento SVG usando un valore numerico.

```csharp
public static TBuilder BaselineShift<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| value | Il valore numerico per baseline shift. |
| tipo | Il tipo di unità di lunghezza. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
