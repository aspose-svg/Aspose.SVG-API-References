---
title: "IDrawingFactory.CreateMatrix"
second_title: "Aspose.SVG for .NET API 参考"
description: "IDrawingFactory CreateMatrix 方法。创建一个与指定矩阵具有相同内容的新矩阵"
type: docs
weight: 30
url: /zh/net/aspose.svg.drawing/idrawingfactory/creatematrix/
---
## CreateMatrix(*[IMatrix](../../imatrix/)*) {#creatematrix_1}

创建一个与指定矩阵具有相同内容的新矩阵。

```csharp
public IMatrix CreateMatrix(IMatrix matrix)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩阵 | IMatrix | 要复制的矩阵。 |

### 返回值

已创建的[`IMatrix`](../../imatrix/)。

### 另请参阅

* interface [IMatrix](../../imatrix/)
* interface [IDrawingFactory](../)
* namespace [Aspose.Svg.Drawing](../../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../../)

---

## CreateMatrix(*float, float, float, float, float, float*) {#creatematrix_2}

使用指定的元素创建一个新矩阵。

```csharp
public IMatrix CreateMatrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m11 | Single | 矩阵第一行第一列的值。 |
| m12 | Single | 矩阵第一行第二列的值。 |
| m21 | Single | 矩阵第二行第一列的值。 |
| m22 | Single | 矩阵第二行第二列的值。 |
| m31 | Single | 矩阵第三行第一列的值。 |
| m32 | Single | 矩阵第三行第二列的值。 |

### 返回值

已创建的[`IMatrix`](../../imatrix/)。

### 另请参阅

* interface [IMatrix](../../imatrix/)
* interface [IDrawingFactory](../)
* namespace [Aspose.Svg.Drawing](../../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../../)

---

## CreateMatrix() {#creatematrix}

创建一个新的单位矩阵。

```csharp
public IMatrix CreateMatrix()
```

### 返回值

已创建的[`IMatrix`](../../imatrix/)。

### 另请参阅

* interface [IMatrix](../../imatrix/)
* interface [IDrawingFactory](../)
* namespace [Aspose.Svg.Drawing](../../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../../)
