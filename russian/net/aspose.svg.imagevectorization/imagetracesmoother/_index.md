---
title: "Класс ImageTraceSmoother"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.ImageVectorization.ImageTraceSmoother. Класс ImageTraceSimplifier отвечает за сглаживание количества точек в кривой, приближённой серией точек трассировки. Этот класс реализует подход ближайшего соседа."
type: docs
weight: 4200
url: /ru/net/aspose.svg.imagevectorization/imagetracesmoother/
---
## ImageTraceSmoother class

Класс ImageTraceSimplifier отвечает за сглаживание количества точек в кривой, аппроксимируемой серией точек трассировки. Этот класс реализует подход ближайшего соседа.

```csharp
public class ImageTraceSmoother : IImageTraceSmoother
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageTraceSmoother](imagetracesmoother/#constructor)() | Инициализирует новый экземпляр класса `ImageTraceSmoother`. |
| [ImageTraceSmoother](imagetracesmoother/#constructor_1)(*int*) | Инициализирует новый экземпляр класса `ImageTraceSmoother`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Extent](../../aspose.svg.imagevectorization/imagetracesmoother/extent/) { get; set; } | Получает или задает размер области, рассматриваемой запросом точки. Должно быть в диапазоне от 1 до 20. Любые более высокие или более низкие значения будут скорректированы до минимального и максимального значений этого диапазона соответственно. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Smooth](../../aspose.svg.imagevectorization/imagetracesmoother/smooth/)(*IEnumerable&lt;PointF&gt;*) | Сглаживает трассировку. |

### См. также

* interface [IImageTraceSmoother](../iimagetracesmoother/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
