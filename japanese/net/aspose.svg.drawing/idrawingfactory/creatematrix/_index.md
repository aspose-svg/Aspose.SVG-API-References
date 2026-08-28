---
title: "IDrawingFactory.CreateMatrix"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IDrawingFactory CreateMatrix メソッド。指定された行列と同じ内容を持つ新しい行列を作成します。"
type: docs
weight: 30
url: /ja/net/aspose.svg.drawing/idrawingfactory/creatematrix/
---
## CreateMatrix(*[IMatrix](../../imatrix/)*) {#creatematrix_1}

指定された行列と同じ内容の新しい行列を作成します。

```csharp
public IMatrix CreateMatrix(IMatrix matrix)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| matrix | IMatrix | コピーする行列です。 |

### 戻り値

作成された[`IMatrix`](../../imatrix/)です。

### 参照

* interface [IMatrix](../../imatrix/)
* interface [IDrawingFactory](../)
* namespace [Aspose.Svg.Drawing](../../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../../)

---

## CreateMatrix(*float, float, float, float, float, float*) {#creatematrix_2}

指定された要素で新しい行列を作成します。

```csharp
public IMatrix CreateMatrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| m11 | Single | 行列の第1行第1列の値です。 |
| m12 | Single | 行列の第1行第2列の値です。 |
| m21 | Single | 行列の第2行第1列の値です。 |
| m22 | Single | 行列の第2行第2列の値です。 |
| m31 | Single | 行列の第3行第1列の値です。 |
| m32 | Single | 行列の第3行第2列の値です。 |

### 戻り値

作成された[`IMatrix`](../../imatrix/)です。

### 参照

* interface [IMatrix](../../imatrix/)
* interface [IDrawingFactory](../)
* namespace [Aspose.Svg.Drawing](../../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../../)

---

## CreateMatrix() {#creatematrix}

新しい単位行列を作成します。

```csharp
public IMatrix CreateMatrix()
```

### 戻り値

作成された[`IMatrix`](../../imatrix/)です。

### 参照

* interface [IMatrix](../../imatrix/)
* interface [IDrawingFactory](../)
* namespace [Aspose.Svg.Drawing](../../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../../)
