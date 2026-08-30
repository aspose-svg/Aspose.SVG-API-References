---
title: "ShapeRendering Enum"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.ShapeRendering enum. Anger renderingsläget för former för SVG-element"
type: docs
weight: 1720
url: /sv/net/aspose.svg.builder/shaperendering/
---
## ShapeRendering enumeration

Anger läget för formrendering för SVG-element.

```csharp
public enum ShapeRendering
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | `0` | Webbläsaren gör avvägningar mellan hastighet, jämnhet och geometrisk precision när den renderar former. |
| OptimizeSpeed | `1` | Webbläsaren prioriterar renderingshastighet framför geometrisk precision och jämnhet. Detta läge kan leda till snabbare rendering men mindre exakta former. |
| CrispEdges | `2` | Webbläsaren försöker bevara skarpa kanter och hörn. Detta läge är användbart för rendering av grafik med raka linjer och kanter. |
| GeometricPrecision | `3` | Webbläsaren betonar geometrisk precision i rendering på bekostnad av hastighet. Detta läge är lämpligt för högkvalitativ rendering där exakt geometri är viktig. |

### Se även

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
