---
title: "SplinePathBuilder.Build"
second_title: "Aspose.SVG för .NET API-referens"
description: "SplinePathBuilder Build-metod. Skapar en jämn bana genom en sekvens av punkter genom att konvertera centripetala CatmullRom-splines till Bezier-kurvor. Denna metod säkerställer en naturlig och mjuk övergång genom varje punkt och skapar en SVG-bana som noggrant följer den angivna trace."
type: docs
weight: 50
url: /sv/net/aspose.svg.imagevectorization/splinepathbuilder/build/
---
## SplinePathBuilder.Build method

Konstruerar en jämn bana genom en sekvens av punkter genom att konvertera centripetala Catmull‑Rom‑splines till Bézier‑kurvor. Denna metod säkerställer en naturlig och jämn övergång genom varje punkt och skapar en SVG‑bana som noggrant följer det angivna spåret.

```csharp
public string Build(IEnumerable<PointF> trace)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| spår | IEnumerable`1 | Sekvensen av punkter som ska interpoleras till en jämn bana. |

### Returvärde

En sträng som representerar SVG-banadata, bestående av Bezier-kurvkommandon och koordinater som approximerar den centripetala Catmull–Rom-splinen.

### Se även

* class [SplinePathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
