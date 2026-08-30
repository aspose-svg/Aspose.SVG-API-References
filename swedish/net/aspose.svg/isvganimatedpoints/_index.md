---
title: "ISVGAnimatedPoints-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.ISVGAnimatedPoints-gränssnitt. SVGAnimatedPoints-gränssnittet stödjer element som har ett points-attribut som innehåller en lista med koordinatvärden och som möjliggör animation av det attributet. Dessutom kommer points-attributet på det ursprungliga elementet som nås via XML DOM, t.ex. genom att anropa getAttribute‑metoden, att återspegla eventuella ändringar som gjorts i points."
type: docs
weight: 4070
url: /sv/net/aspose.svg/isvganimatedpoints/
---
## ISVGAnimatedPoints interface

SVGAnimatedPoints‑gränssnittet stödjer element som har ett ‘points’-attribut som innehåller en lista med koordinatvärden och som möjliggör att animera det attributet. Dessutom kommer ‘points’-attributet på det ursprungliga elementet som nås via XML‑DOM (t.ex. med getAttribute()-metodanrop) att återspegla alla ändringar som gjorts i points.

```csharp
public interface ISVGAnimatedPoints
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AnimatedPoints](../../aspose.svg/isvganimatedpoints/animatedpoints/) { get; } | Tillhandahåller åtkomst till det aktuella animerade innehållet i attributet ‘points’. Om det angivna attributet eller egenskapen är animerad, innehåller det det aktuella animerade värdet för attributet eller egenskapen. Om det angivna attributet eller egenskapen för närvarande inte är animerad, innehåller det samma värde som points. |
| [Points](../../aspose.svg/isvganimatedpoints/points/) { get; } | Tillhandahåller åtkomst till basen (dvs. statiska) innehållet i attributet ‘points’. |

### Se även

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
