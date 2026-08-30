---
title: "FillRule enum"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.FillRule enum. Anger regeln för att bestämma vilka delar av en form som är innanför eller utanför i SVG-grafik."
type: docs
weight: 270
url: /sv/net/aspose.svg.builder/fillrule/
---
## FillRule enumeration

Anger regeln för att bestämma vilka delar av en form som är innanför eller utanför i SVG-grafik.

```csharp
public enum FillRule
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Nonzero | `0` | Den icke‑noll winding‑regeln: Bestämmer "insiden" av en punkt i formen genom att rita en stråle från den punkten till oändligheten i någon riktning och räkna antalet bansegment från den givna formen som strålen korsar. Om detta antal är udda är punkten innanför; om det är jämnt är den utanför. |
| Evenodd | `1` | Den jämna‑udda winding‑regeln: Bestämmer "insiden" av en punkt i formen genom att rita en stråle från den punkten till oändligheten i någon riktning och räkna antalet bansegment från den givna formen som strålen korsar. Om detta antal är jämnt är punkten utanför; om det är udda är den innanför. |

### Se även

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
