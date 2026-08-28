---
title: "SVGBuilderExtensions.X"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions X. Imposta l'attributo x per un elemento SVG"
type: docs
weight: 2360
url: /it/net/aspose.svg.builder/svgbuilderextensions/x/
---
## X<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#x_1}

Imposta l'attributo 'x' per un elemento SVG.

```csharp
public static TBuilder X<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IXAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| value | Il valore dell'attributo 'x'. |
| tipo | Il tipo di unità di lunghezza (il valore predefinito è pixel). |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IXAttributeSetter](../../ixattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## X<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#x}

Imposta l'attributo 'x' per posizionare il contenuto testuale lungo l'asse x.

```csharp
public static TBuilder X<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| tipo | Il tipo di unità di lunghezza per i valori. |
| valori | I valori di posizione dell'asse x. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

## Osservazioni

Questo metodo imposta l'attributo 'x', che determina le posizioni orizzontali dell'elemento di testo.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
