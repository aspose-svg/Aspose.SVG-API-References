---
title: "Класс BezierPathBuilder"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.ImageVectorization.BezierPathBuilder. Класс BezierPathBuilder отвечает за построение пути Безье из заданного набора точек. Он аппроксимирует трассу точек кривой Безье, оптимизируя количество сегментов для точного соответствия оригинальной трассе при минимизации сложности."
type: docs
weight: 4150
url: /ru/net/aspose.svg.imagevectorization/bezierpathbuilder/
---
## BezierPathBuilder class

Класс `BezierPathBuilder` отвечает за построение пути Безье из заданного набора точек. Он аппроксимирует трассу точек кривой Безье, оптимизируя количество сегментов для точного соответствия оригинальной трассе при минимизации сложности.

```csharp
public class BezierPathBuilder : IPathBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BezierPathBuilder](bezierpathbuilder/)() | Инициализирует новый экземпляр класса `BezierPathBuilder`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ErrorThreshold](../../aspose.svg.imagevectorization/bezierpathbuilder/errorthreshold/) { get; set; } | Получает или задает порог ошибки. Этот параметр определяет максимальное отклонение точек от подогнанной кривой. По умолчанию он равен 30. |
| [MaxIterations](../../aspose.svg.imagevectorization/bezierpathbuilder/maxiterations/) { get; set; } | Получает или задает порог ошибки. Этот параметр определяет количество итераций метода наименьших квадратов. По умолчанию он равен 30. |
| [TraceSmoother](../../aspose.svg.imagevectorization/bezierpathbuilder/tracesmoother/) { get; set; } | Получает или задает сглаживатель трассы. |

## Методы

| Имя | Описание |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/bezierpathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | Создаёт оптимизированный путь Безье из последовательности точек трассы. Метод аппроксимирует заданную трассу кривой Безье, используя комбинацию линейных и криволинейных сегментов. Он стремится минимизировать количество сегментов, обеспечивая при этом точное соответствие пути оригинальной трассе. |

### См. также

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
