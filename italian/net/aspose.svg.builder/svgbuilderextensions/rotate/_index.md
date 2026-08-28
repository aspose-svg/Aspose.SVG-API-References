---
title: "SVGBuilderExtensions.Rotate"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo Rotate di SVGBuilderExtensions. Imposta gli angoli di rotazione per caratteri individuali o segmenti del contenuto testuale."
type: docs
weight: 2000
url: /it/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

Imposta gli angoli di rotazione per i singoli caratteri o segmenti del contenuto testuale.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| valori | Un array di angoli di rotazione in gradi. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

## Osservazioni

Questo metodo imposta l'attributo 'rotate' con valori multipli, consentendo la rotazione individuale di ogni carattere o segmento di testo.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

Imposta un unico angolo di rotazione per l'intero contenuto testuale.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | L'angolo di rotazione in gradi. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

## Osservazioni

Questo metodo imposta l'attributo 'rotate' con un valore singolo, applicando lo stesso angolo di rotazione a tutto il contenuto testuale.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
