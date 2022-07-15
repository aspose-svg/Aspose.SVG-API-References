---
title: ImageTraceSimplifier
second_title: Справочник по Aspose.SVG для .NET API
description: Класс ImageTraceSimplifier отвечает за уменьшение количества точек на кривой аппроксимируемой серией точек трассировки.
type: docs
weight: 2100
url: /ru/net/aspose.svg.imagevectorization/imagetracesimplifier/
---
## ImageTraceSimplifier class

Класс ImageTraceSimplifier отвечает за уменьшение количества точек на кривой, аппроксимируемой серией точек трассировки.

```csharp
public class ImageTraceSimplifier : IImageTraceSimplifier
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageTraceSimplifier](imagetracesimplifier#constructor)() | Инициализирует новый экземпляр класса[`ImageTraceSimplifier`](../imagetracesimplifier). |
| [ImageTraceSimplifier](imagetracesimplifier#constructor_1)(float) | Инициализирует новый экземпляр класса[`ImageTraceSimplifier`](../imagetracesimplifier). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Tolerance](../../aspose.svg.imagevectorization/imagetracesimplifier/tolerance) { get; set; } | Значение допуска определяет максимальную допустимую погрешность для исключения точки из трассировки. Он должен быть в диапазоне от 0 до 4. Любые более высокие или более низкие значения будут совмещены с минимальным и максимальным значениями этого диапазона соответственно. Значение по умолчанию — 0,3. |

## Методы

| Имя | Описание |
| --- | --- |
| [Simplify](../../aspose.svg.imagevectorization/imagetracesimplifier/simplify)(IEnumerable&lt;PointF&gt;) | Уменьшает количество точек в списке точек трассировки. |

### Смотрите также

* interface [IImageTraceSimplifier](../iimagetracesimplifier)
* пространство имен [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization)
* сборка [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->