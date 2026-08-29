---
title: "SVGGeometryElement.Combine"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGGeometryElement Combine-methode. Combineert deze geometrie met een andere SVG-geometrie met behulp van een booleaanse bewerking en retourneert een nieuw pad-element dat het resultaat bevat."
type: docs
weight: 20
url: /nl/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

Combineert deze geometrie met een andere SVG-geometrie met behulp van een booleaanse bewerking, en retourneert een nieuw `<path>`-element dat het resultaat bevat.

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | De andere geometrie om mee te combineren. Moet zich in hetzelfde document bevinden. |
| op | BooleanPathOp | De booleaanse operator die moet worden toegepast: Union (A UNION B), Difference (A - B), Intersection (A INTERSECT B) of Exclusion (XOR). |

### Retourwaarde

Een nieuwe [`SVGPathElement`](../../svgpathelement/) waarvan het `d`-attribuut het resultaat codeert in de root `<svg>`-gebruikersruimte (CSS px). Het element wordt niet aan de DOM toegevoegd.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentNullException | Gegooid als *geometryElement* null is. |
| InvalidOperationException | Wordt gegooid als dit element geen eigenaardocument heeft. |
| NotSupportedException | Wordt gegooid wanneer booleaanse padbewerkingen niet beschikbaar zijn; deze functie vereist de SkiaSharp-backend (installeer het Aspose.SVG.Drawing.SkiaSharp-pakket). |

### Zie ook

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
