---
title: "SVGBuilderExtensions.Y"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo Y di SVGBuilderExtensions. Imposta l'attributo y per un elemento SVG"
type: docs
weight: 2400
url: /it/net/aspose.svg.builder/svgbuilderextensions/y/
---
## Y<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#y_1}

Imposta l'attributo 'y' per un elemento SVG.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IYAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| value | Il valore per l'attributo 'y'. |
| tipo | Il tipo di unità di lunghezza (il valore predefinito è pixel). |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IYAttributeSetter](../../iyattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Y<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#y}

Imposta l'attributo 'y' per posizionare il contenuto testuale lungo l'asse y.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| tipo | Il tipo di unità di lunghezza per i valori. |
| valori | I valori di posizione sull'asse y. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

## Osservazioni

Questo metodo imposta l'attributo 'y', che determina la posizione verticale dell'elemento di testo.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
