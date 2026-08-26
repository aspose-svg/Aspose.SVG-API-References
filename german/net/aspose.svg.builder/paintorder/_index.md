---
title: "PaintOrder Enum"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.PaintOrder Enum. Gibt die Reihenfolge an, in der Füllung, Kontur und Marker auf SVG-Elemente angewendet werden."
type: docs
weight: 990
url: /de/net/aspose.svg.builder/paintorder/
---
## PaintOrder enumeration

Gibt die Reihenfolge an, in der fill, stroke und Marker auf SVG-Elemente angewendet werden.

```csharp
public enum PaintOrder
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Normal | `0` | Die Standard-Malreihenfolge: zuerst Füllung, dann Kontur und schließlich Marker. |
| Fill | `1` | Nur die Füllung malen. |
| Stroke | `2` | Nur die Kontur malen. |
| Markers | `3` | Nur die Marker malen. |
| FillStroke | `4` | Malen Sie in der Reihenfolge von fill, dann stroke. |
| FillMarkers | `5` | Malen Sie in der Reihenfolge von fill, dann markers. |
| StrokeFill | `6` | Malen Sie in der Reihenfolge von stroke, dann fill. |
| StrokeMarkers | `7` | Malen Sie in der Reihenfolge von stroke, dann markers. |
| MarkersFill | `8` | Malen Sie in der Reihenfolge von markers, dann fill. |
| MarkersStroke | `9` | Malen Sie in der Reihenfolge von markers, dann stroke. |
| FillStrokeMarkers | `10` | Malen Sie in der Reihenfolge von fill, dann stroke und schließlich markers. |
| FillMarkersStroke | `11` | Malen Sie in der Reihenfolge von fill, dann markers und schließlich stroke. |
| StrokeFillMarkers | `12` | Malen Sie in der Reihenfolge von stroke, dann fill und schließlich markers. |
| StrokeMarkersFill | `13` | Malen Sie in der Reihenfolge von stroke, dann markers und schließlich fill. |
| MarkersFillStroke | `14` | Malen Sie in der Reihenfolge von markers, dann fill und schließlich stroke. |
| MarkersStrokeFill | `15` | Malen Sie in der Reihenfolge von markers, dann stroke und schließlich fill. |

### Siehe auch

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
