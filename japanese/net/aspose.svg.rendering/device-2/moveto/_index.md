---
title: "Device-2.MoveTo"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Device MoveTo メソッド。現在の点をパラメータ pt の座標へ移動させ、接続線分を省略して新しいサブパスを開始します。現在のパス内で前のパス構築メソッドが MoveTo でも、新しい MoveTo がそれを上書きし、以前の MoveTo 操作の痕跡はパスに残りません"
type: docs
weight: 220
url: /ja/net/aspose.svg.rendering/device-2/moveto/
---
## Device<TGraphicContext,TRenderingOptions>.MoveTo method

パラメータ pt の座標に現在の点を移動させ、接続線セグメントを省略することで新しいサブパスを開始します。現在のパスで前のパス構築メソッドが "MoveTo" でも、新しい "MoveTo" がそれを上書きします。パス内に前の "MoveTo" 操作の痕跡は残りません。

```csharp
public virtual void MoveTo(PointF pt)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pt | PointF | パスを移動させる点。 |

### 参照

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
