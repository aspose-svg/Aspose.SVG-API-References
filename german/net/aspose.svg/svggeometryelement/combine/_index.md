---
title: "SVGGeometryElement.Combine"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGGeometryElement Combine‑Methode. Kombiniert diese Geometrie mit einer anderen SVG‑Geometrie mittels einer booleschen Operation und gibt ein neues Pfadelement zurück, das das Ergebnis enthält."
type: docs
weight: 20
url: /de/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

Kombiniert diese Geometrie mit einer anderen SVG‑Geometrie mittels einer booleschen Operation und gibt ein neues `<path>`‑Element zurück, das das Ergebnis enthält.

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | Die andere Geometrie, mit der kombiniert werden soll. Sie muss im selben Dokument sein. |
| op | BooleanPathOp | Der anzuwendende boolesche Operator: Union (A UNION B), Differenz (A - B), Schnittmenge (A INTERSECT B) oder Ausschluss (XOR). |

### Rückgabewert

Ein neues [`SVGPathElement`](../../svgpathelement/), dessen `d`-Attribut das Ergebnis im Root-`<svg>`-Benutzerraum (CSS‑px) kodiert. Das Element wird nicht an das DOM angehängt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Ausgelöst, wenn *geometryElement* null ist. |
| InvalidOperationException | Ausgelöst, wenn dieses Element kein Eigentümerdokument hat. |
| NotSupportedException | Ausgelöst, wenn boolesche Pfadoperationen nicht verfügbar sind; diese Funktion erfordert das SkiaSharp‑Backend (installieren Sie das Aspose.SVG.Drawing.SkiaSharp‑Paket). |

### Siehe auch

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
