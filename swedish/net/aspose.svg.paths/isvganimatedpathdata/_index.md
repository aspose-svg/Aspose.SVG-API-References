---
title: "ISVGAnimatedPathData gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Paths.ISVGAnimatedPathData gränssnitt. Det SVGAnimatedPathData‑gränssnittet stödjer element som har ett d‑attribut som innehåller SVG‑sökvägsdata och möjliggör att animera det attributet"
type: docs
weight: 4550
url: /sv/net/aspose.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

SVGAnimatedPathData‑gränssnittet stöder element som har ett ‘d’-attribut som innehåller SVG‑sökvägsdata, och stöder möjligheten att animera det attributet.

```csharp
public interface ISVGAnimatedPathData
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AnimatedPathSegList](../../aspose.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | Tillhandahåller åtkomst till det aktuella animerade innehållet i ‘d’-attributet i ett format som matchar en‑till‑en med SVG:s syntax. Om det angivna attributet eller egenskapen är under animation, innehåller det det aktuella animerade värdet för attributet eller egenskapen, och både objektet självt och dess innehåll är skrivskyddade. Om det angivna attributet eller egenskapen för närvarande inte är animerad, innehåller det samma värde som pathSegList. |
| [PathSegList](../../aspose.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | Tillhandahåller åtkomst till de grundläggande (dvs. statiska) innehållen i ‘d’-attributet i ett format som matchar en‑till‑en med SVG:s syntax. Således, om ‘d’-attributet har ett \"absolut moveto (M)\" och ett \"absolut arcto (A)\"‑kommando, kommer pathSegList att ha två poster: ett SVG_PATHSEG_MOVETO_ABS och ett SVG_PATHSEG_ARC_ABS. |

### Se även

* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)
