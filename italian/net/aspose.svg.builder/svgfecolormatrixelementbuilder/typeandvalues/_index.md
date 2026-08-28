---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo TypeAndValues di SVGFEColorMatrixElementBuilder. Imposta gli attributi type e values dell'elemento feColorMatrix specificando l'operazione della matrice di colore e i relativi parametri"
type: docs
weight: 30
url: /it/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

Imposta gli attributi 'type' e 'values' dell'elemento feColorMatrix, specificando l'operazione della matrice dei colori e i relativi parametri.

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | ColorMatrixOperation | Il valore enum ColorMatrixOperation che rappresenta il tipo di operazione della matrice di colore. |
| valori | Double[] | I parametri per l'operazione della matrice di colore. |

### Valore di ritorno

L'istanza corrente del builder.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Generato quando i valori forniti non corrispondono ai requisiti del tipo specificato. |
| NotSupportedException | Generato quando viene fornito un tipo di operazione di matrice non supportato. |

### Vedi anche

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
