---
title: "IMatrix.Scale"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IMatrix Scale メソッド。指定された順序で指定されたスケール係数に従って行列を拡大縮小します。"
type: docs
weight: 160
url: /ja/net/aspose.svg.drawing/imatrix/scale/
---
## Scale(*float, float, [WebMatrixOrder](../../webmatrixorder/)*) {#scale_1}

指定された順序で、指定されたスケール係数に従って行列を拡大縮小します。

```csharp
public void Scale(float scaleX, float scaleY, WebMatrixOrder order)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| scaleX | Single | x 軸に沿ったスケール係数です。 |
| scaleY | Single | y 軸に沿ったスケール係数です。 |
| order | WebMatrixOrder | スケーリングが適用される順序です。 |

### 参照

* enum [WebMatrixOrder](../../webmatrixorder/)
* interface [IMatrix](../)
* namespace [Aspose.Svg.Drawing](../../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../../)

---

## Scale(*float, float*) {#scale}

指定されたスケール係数で行列を均等に拡大縮小します。

```csharp
public void Scale(float scaleX, float scaleY)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| scaleX | Single | 一様スケール係数です。 |
| scaleY | Single | 一様スケール係数です。 |

### 参照

* interface [IMatrix](../)
* namespace [Aspose.Svg.Drawing](../../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../../)
