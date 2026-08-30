---
title: "SVGGeometryElement.Combine"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGGeometryElement Combine‑metod. Kombinerar denna geometri med en annan SVG‑geometri med en boolesk operation och returnerar ett nytt path‑element som innehåller resultatet."
type: docs
weight: 20
url: /sv/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

Kombinerar denna geometri med en annan SVG-geometri med en boolesk operation och returnerar ett nytt `<path>`-element som innehåller resultatet.

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | Den andra geometrin att kombinera med. Måste finnas i samma dokument. |
| op | BooleanPathOp | Den booleska operatorn att använda: Union (A UNION B), Differens (A - B), Intersektion (A INTERSECT B) eller Exklusion (XOR). |

### Returvärde

Ett nytt [`SVGPathElement`](../../svgpathelement/) vars `d`‑attribut kodar resultatet i rot‑`<svg>`‑användarutrymmet (CSS‑px). Elementet läggs inte till i DOM‑en.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas om *geometryElement* är null. |
| InvalidOperationException | Kastas om detta element saknar ett ägardokument. |
| NotSupportedException | Kastas när boolska banoperationer är otillgängliga; den här funktionen kräver SkiaSharp‑backend (installera paketet Aspose.SVG.Drawing.SkiaSharp). |

### Se även

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
