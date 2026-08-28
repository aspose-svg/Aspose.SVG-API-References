---
title: "ShapeRendering 列挙型"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.ShapeRendering 列挙型。SVG 要素のシェイプレンダリングモードを指定します"
type: docs
weight: 1720
url: /ja/net/aspose.svg.builder/shaperendering/
---
## ShapeRendering enumeration

SVG 要素のシェイプレンダリングモードを指定します。

```csharp
public enum ShapeRendering
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Auto | `0` | ブラウザーは形状をレンダリングする際、速度、滑らかさ、幾何精度の間でトレードオフを行います。 |
| OptimizeSpeed | `1` | ブラウザーは幾何精度や滑らかさよりもレンダリング速度を重視します。このモードはより高速なレンダリングを実現しますが、形状の精度が低下する可能性があります。 |
| CrispEdges | `2` | ブラウザーは鋭いエッジやコーナーを保持しようとします。このモードは直線やエッジを持つグラフィックのレンダリングに有用です。 |
| GeometricPrecision | `3` | ブラウザーは速度を犠牲にしてレンダリング時の幾何精度を重視します。このモードは正確なジオメトリが重要な高品質レンダリングに適しています。 |

### 参照

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
