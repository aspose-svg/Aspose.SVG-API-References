---
title: "PaintOrder Enum'ı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.PaintOrder enum. Doldurma, kenar çizgisi ve işaretçilerin SVG öğelerine uygulanma sırasını belirtir"
type: docs
weight: 990
url: /tr/net/aspose.svg.builder/paintorder/
---
## PaintOrder enumeration

SVG öğelerine doldurma, kenar çizgi ve işaretçilerin uygulanma sırasını belirtir.

```csharp
public enum PaintOrder
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Normal | `0` | Varsayılan boyama sırası: önce doldurma, ardından kenar çizgisi ve sonunda işaretçiler. |
| Fill | `1` | Sadece doldurmayı boya. |
| Stroke | `2` | Sadece kenar çizgisini boya. |
| Markers | `3` | Sadece işaretçileri boya. |
| FillStroke | `4` | Doldurma, ardından kenar çizgisi sırasıyla boya. |
| FillMarkers | `5` | Doldurma, ardından işaretçiler sırasıyla boya. |
| StrokeFill | `6` | Kenar çizgisi, ardından doldurma sırasıyla boya. |
| StrokeMarkers | `7` | Kenar çizgisi, ardından işaretçiler sırasıyla boya. |
| MarkersFill | `8` | İşaretçiler, ardından doldurma sırasıyla boya. |
| MarkersStroke | `9` | İşaretçiler, ardından kenar çizgisi sırasıyla boya. |
| FillStrokeMarkers | `10` | Doldurma, ardından kenar çizgisi ve sonunda işaretçiler sırasıyla boya. |
| FillMarkersStroke | `11` | Doldurma, ardından işaretçiler ve sonunda kenar çizgisi sırasıyla boya. |
| StrokeFillMarkers | `12` | Kenar çizgisi, ardından doldurma ve sonunda işaretçiler sırasıyla boya. |
| StrokeMarkersFill | `13` | Kenar çizgisi, ardından işaretçiler ve sonunda doldurma sırasıyla boya. |
| MarkersFillStroke | `14` | İşaretçiler, ardından doldurma ve sonunda kenar çizgisi sırasıyla boya. |
| MarkersStrokeFill | `15` | İşaretçiler, ardından kenar çizgisi ve sonunda doldurma sırasıyla boya. |

### Ayrıca Bakınız

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
