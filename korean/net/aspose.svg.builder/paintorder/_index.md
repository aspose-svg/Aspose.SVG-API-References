---
title: "PaintOrder 열거형"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.PaintOrder 열거형. fill, stroke 및 markers가 SVG 요소에 적용되는 순서를 지정합니다."
type: docs
weight: 990
url: /ko/net/aspose.svg.builder/paintorder/
---
## PaintOrder enumeration

SVG 요소에 fill, stroke 및 마커가 적용되는 순서를 지정합니다.

```csharp
public enum PaintOrder
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Normal | `0` | 기본 페인트 순서: 먼저 fill, 그 다음 stroke, 마지막으로 markers. |
| Fill | `1` | fill만 그립니다. |
| Stroke | `2` | stroke만 그립니다. |
| Markers | `3` | markers만 그립니다. |
| FillStroke | `4` | fill, 그 다음 stroke 순서대로 그립니다. |
| FillMarkers | `5` | fill, 그 다음 markers 순서대로 그립니다. |
| StrokeFill | `6` | stroke, 그 다음 fill 순서대로 그립니다. |
| StrokeMarkers | `7` | stroke, 그 다음 markers 순서대로 그립니다. |
| MarkersFill | `8` | 마커 순서대로 그리고, 그 다음 채우기. |
| MarkersStroke | `9` | 마커 순서대로 그리고, 그 다음 스트로크. |
| FillStrokeMarkers | `10` | 채우기 순서대로 그리고, 그 다음 스트로크, 마지막으로 마커. |
| FillMarkersStroke | `11` | 채우기 순서대로 그리고, 그 다음 마커, 마지막으로 스트로크. |
| StrokeFillMarkers | `12` | 스트로크 순서대로 그리고, 그 다음 채우기, 마지막으로 마커. |
| StrokeMarkersFill | `13` | 스트로크 순서대로 그리고, 그 다음 마커, 마지막으로 채우기. |
| MarkersFillStroke | `14` | 마커 순서대로 그리고, 그 다음 채우기, 마지막으로 스트로크. |
| MarkersStrokeFill | `15` | 마커 순서대로 그리고, 그 다음 스트로크, 마지막으로 채우기. |

### 또 보기

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
