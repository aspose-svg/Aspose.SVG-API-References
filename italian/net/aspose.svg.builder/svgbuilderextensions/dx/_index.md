---
title: "SVGBuilderExtensions.Dx"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions Dx. Imposta l'attributo dx per regolare la posizione orizzontale di ogni carattere nel testo"
type: docs
weight: 770
url: /it/net/aspose.svg.builder/svgbuilderextensions/dx/
---
## Dx<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#dx}

Imposta l'attributo 'dx' per regolare la posizione orizzontale di ciascun carattere nel testo.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| tipo | Il tipo di unità di lunghezza per i valori. |
| valori | I valori di regolazione orizzontale per ogni carattere. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

## Osservazioni

Questo metodo consente un controllo fine della spaziatura orizzontale dei caratteri nel testo.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dx<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dx_1}

Imposta un singolo valore di aggiustamento orizzontale per il contenuto del testo.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | Il valore di regolazione orizzontale. |
| tipo | Il tipo di unità di lunghezza per il valore. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

## Osservazioni

Questo metodo imposta l'attributo 'dx' con un singolo valore, regolando la posizione orizzontale del contenuto testuale.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
