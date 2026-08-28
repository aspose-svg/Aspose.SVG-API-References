---
title: "SVGGeometryElement.Combine"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo Combine di SVGGeometryElement. Combina questa geometria con un'altra geometria SVG usando un'operazione booleana e restituisce un nuovo elemento path contenente il risultato."
type: docs
weight: 20
url: /it/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

Combina questa geometria con un'altra geometria SVG usando un'operazione booleana e restituisce un nuovo elemento `<path>` contenente il risultato.

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | L'altra geometria da combinare. Deve trovarsi nello stesso documento. |
| op | BooleanPathOp | L'operatore booleano da applicare: Union (A UNION B), Difference (A - B), Intersection (A INTERSECT B) o Exclusion (XOR). |

### Valore di ritorno

Un nuovo [`SVGPathElement`](../../svgpathelement/) il cui attributo `d` codifica il risultato nello spazio utente radice `<svg>` (px CSS). L'elemento non viene aggiunto al DOM.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lanciata se *geometryElement* è null. |
| InvalidOperationException | Lanciata se questo elemento non ha un documento proprietario. |
| NotSupportedException | Lanciata quando le operazioni booleane su path non sono disponibili; questa funzionalità richiede il backend SkiaSharp (installare il pacchetto Aspose.SVG.Drawing.SkiaSharp). |

### Vedi anche

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
