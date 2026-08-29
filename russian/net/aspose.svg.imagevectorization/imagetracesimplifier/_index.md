---
title: "Класс ImageTraceSimplifier"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.ImageVectorization.ImageTraceSimplifier. Класс ImageTraceSimplifier отвечает за уменьшение количества точек в кривой, приближённой серией точек трассировки."
type: docs
weight: 4190
url: /ru/net/aspose.svg.imagevectorization/imagetracesimplifier/
---
## ImageTraceSimplifier class

Класс ImageTraceSimplifier отвечает за уменьшение количества точек в кривой, аппроксимируемой серией точек трассировки.

```csharp
public class ImageTraceSimplifier : IImageTraceSimplifier
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageTraceSimplifier](imagetracesimplifier/#constructor)() | Инициализирует новый экземпляр класса `ImageTraceSimplifier`. |
| [ImageTraceSimplifier](imagetracesimplifier/#constructor_1)(*float*) | Инициализирует новый экземпляр класса `ImageTraceSimplifier`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Tolerance](../../aspose.svg.imagevectorization/imagetracesimplifier/tolerance/) { get; set; } | Значение допуска определяет максимальную ошибку, допускаемую для удаления точки из трассировки. Должно быть в диапазоне от 0 до 4. Любые более высокие или более низкие значения будут скорректированы до минимального и максимального значений этого диапазона соответственно. Значение по умолчанию — 0,3. |

## Методы

| Имя | Описание |
| --- | --- |
| [Simplify](../../aspose.svg.imagevectorization/imagetracesimplifier/simplify/)(*IEnumerable&lt;PointF&gt;*) | Уменьшает количество точек в списке точек трассировки. |

### См. также

* interface [IImageTraceSimplifier](../iimagetracesimplifier/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
