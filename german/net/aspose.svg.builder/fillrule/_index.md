---
title: "FillRule Aufzählung"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.FillRule Aufzählung. Gibt die Regel an, um zu bestimmen, welche Teile einer Form in SVG-Grafiken innen oder außen liegen."
type: docs
weight: 270
url: /de/net/aspose.svg.builder/fillrule/
---
## FillRule enumeration

Gibt die Regel an, um zu bestimmen, welche Teile einer Form in SVG-Grafiken innen oder außen liegen.

```csharp
public enum FillRule
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Nonzero | `0` | Die Nicht-Null-Windungsregel: Bestimmt die "Innenlage" eines Punktes in der Form, indem ein Strahl von diesem Punkt in beliebiger Richtung ins Unendliche gezogen wird und die Anzahl der Pfadsegmente der gegebenen Form gezählt wird, die der Strahl schneidet. Ist diese Zahl ungerade, liegt der Punkt innen; ist sie gerade, liegt er außen. |
| Evenodd | `1` | Die Gerade-Ungerade-Windungsregel: Bestimmt die "Innenlage" eines Punktes in der Form, indem ein Strahl von diesem Punkt in beliebiger Richtung ins Unendliche gezogen wird und die Anzahl der Pfadsegmente der gegebenen Form gezählt wird, die der Strahl schneidet. Ist diese Zahl gerade, liegt der Punkt außen; ist sie ungerade, liegt er innen. |

### Siehe auch

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
