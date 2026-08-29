---
title: "Класс SplinePathBuilder"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.ImageVectorization.SplinePathBuilder. Класс SplinePathBuilder предназначен для построения гладкого пути путём преобразования центростремительных сплайнов CatmullRom в кривые Безье. Он предоставляет метод для генерации пути, который плавно интерполирует набор точек, обеспечивая баланс между точностью к точкам и гладкостью кривой."
type: docs
weight: 4230
url: /ru/net/aspose.svg.imagevectorization/splinepathbuilder/
---
## SplinePathBuilder class

Класс `SplinePathBuilder` предназначен для построения гладкого пути путём преобразования центростремительных сплайнов Catmull–Rom в кривые Безье. Он предоставляет метод для генерации пути, который плавно интерполирует набор точек, обеспечивая баланс между точностью к точкам и гладкостью кривой.

```csharp
public class SplinePathBuilder : IPathBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SplinePathBuilder](splinepathbuilder/#constructor)() | Инициализирует новый экземпляр класса `SplinePathBuilder`. |
| [SplinePathBuilder](splinepathbuilder/#constructor_2)(*float*) | Инициализирует новый экземпляр класса `SplinePathBuilder`. |
| [SplinePathBuilder](splinepathbuilder/#constructor_1)(*[IImageTraceSmoother](../iimagetracesmoother/), [IImageTraceSimplifier](../iimagetracesimplifier/), float*) | Инициализирует новый экземпляр класса `SplinePathBuilder`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Tension](../../aspose.svg.imagevectorization/splinepathbuilder/tension/) { get; set; } | Значение натяжения влияет на то, насколько резко кривая изгибается в (интерполированных) контрольных точках. Оно должно находиться в диапазоне от 0 до 1. Любые более высокие или более низкие значения будут выравнены соответственно с минимальными и максимальными значениями этого диапазона. |
| [TraceSimplifier](../../aspose.svg.imagevectorization/splinepathbuilder/tracesimplifier/) { get; set; } | Получает или задает упрощатель трассы. |
| [TraceSmoother](../../aspose.svg.imagevectorization/splinepathbuilder/tracesmoother/) { get; set; } | Получает или задает сглаживатель трассы. |

## Методы

| Имя | Описание |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/splinepathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | Создаёт плавный путь через последовательность точек, преобразуя центростремительные сплайны Catmull–Rom в кривые Безье. Этот метод обеспечивает естественный и плавный переход через каждую точку, создавая SVG‑путь, который точно следует предоставленной трассе. |

### См. также

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
