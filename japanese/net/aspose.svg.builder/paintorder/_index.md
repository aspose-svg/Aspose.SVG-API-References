---
title: "PaintOrder 列挙体"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.PaintOrder 列挙体。fill、stroke、marker が SVG 要素に適用される順序を指定します。"
type: docs
weight: 990
url: /ja/net/aspose.svg.builder/paintorder/
---
## PaintOrder enumeration

SVG 要素に fill、stroke、マーカーが適用される順序を指定します。

```csharp
public enum PaintOrder
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Normal | `0` | デフォルトの描画順序: 最初に fill、次に stroke、最後に marker です。 |
| Fill | `1` | fill のみを描画します。 |
| Stroke | `2` | stroke のみを描画します。 |
| Markers | `3` | marker のみを描画します。 |
| FillStroke | `4` | fill の後に stroke の順序で描画します。 |
| FillMarkers | `5` | fill の後に marker の順序で描画します。 |
| StrokeFill | `6` | stroke の後に fill の順序で描画します。 |
| StrokeMarkers | `7` | stroke の後に marker の順序で描画します。 |
| MarkersFill | `8` | マーカーの順に描画し、次に塗りつぶします。 |
| MarkersStroke | `9` | マーカーの順に描画し、次に輪郭線を描きます。 |
| FillStrokeMarkers | `10` | 塗りつぶしの順に描画し、次に輪郭線、最後にマーカーを描きます。 |
| FillMarkersStroke | `11` | 塗りつぶしの順に描画し、次にマーカー、最後に輪郭線を描きます。 |
| StrokeFillMarkers | `12` | 輪郭線の順に描画し、次に塗りつぶし、最後にマーカーを描きます。 |
| StrokeMarkersFill | `13` | 輪郭線の順に描画し、次にマーカー、最後に塗りつぶしを描きます。 |
| MarkersFillStroke | `14` | マーカーの順に描画し、次に塗りつぶし、最後に輪郭線を描きます。 |
| MarkersStrokeFill | `15` | マーカーの順に描画し、次に輪郭線、最後に塗りつぶしを描きます。 |

### 参照

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
