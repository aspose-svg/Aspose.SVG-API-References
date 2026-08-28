---
title: "Enum PaintOrder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Aspose.Svg.Builder.PaintOrder enum. Specifica l'ordine in cui riempimento, contorno e marcatori vengono applicati agli elementi SVG"
type: docs
weight: 990
url: /it/net/aspose.svg.builder/paintorder/
---
## PaintOrder enumeration

Specifica l'ordine in cui fill, stroke e marcatori vengono applicati agli elementi SVG.

```csharp
public enum PaintOrder
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Normal | `0` | L'ordine di pittura predefinito: prima il riempimento, poi il contorno e infine i marcatori. |
| Fill | `1` | Dipingi solo il riempimento. |
| Stroke | `2` | Dipingi solo il contorno. |
| Markers | `3` | Dipingi solo i marcatori. |
| FillStroke | `4` | Dipingi nell'ordine di riempimento, poi contorno. |
| FillMarkers | `5` | Dipingi nell'ordine di riempimento, poi marcatori. |
| StrokeFill | `6` | Dipingi nell'ordine di contorno, poi riempimento. |
| StrokeMarkers | `7` | Dipingi nell'ordine di contorno, poi marcatori. |
| MarkersFill | `8` | Dipingi nell'ordine di marcatori, poi riempimento. |
| MarkersStroke | `9` | Dipingi nell'ordine di marcatori, poi contorno. |
| FillStrokeMarkers | `10` | Dipingi nell'ordine di riempimento, poi contorno e infine marcatori. |
| FillMarkersStroke | `11` | Dipingi nell'ordine di riempimento, poi marcatori e infine contorno. |
| StrokeFillMarkers | `12` | Dipingi nell'ordine di contorno, poi riempimento e infine marcatori. |
| StrokeMarkersFill | `13` | Dipingi nell'ordine di contorno, poi marcatori e infine riempimento. |
| MarkersFillStroke | `14` | Dipingi nell'ordine di marcatori, poi riempimento e infine contorno. |
| MarkersStrokeFill | `15` | Dipingi nell'ordine di marcatori, poi contorno e infine riempimento. |

### Vedi anche

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
