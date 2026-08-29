---
title: "Интерфейс IDrawingFactory"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Drawing.IDrawingFactory. Представляет фабрику для создания объектов, связанных с рисованием"
type: docs
weight: 3460
url: /ru/net/aspose.svg.drawing/idrawingfactory/
---
## IDrawingFactory interface

Представляет фабрику для создания объектов, связанных с рисованием.

```csharp
public interface IDrawingFactory : IDisposable
```

## Методы

| Имя | Описание |
| --- | --- |
| [CreateInterpolationColor](../../aspose.svg.drawing/idrawingfactory/createinterpolationcolor/)(*Color, float*) | Создает интерполяционный цвет с указанным цветом и позицией. |
| [CreateLinearGradientBrush](../../aspose.svg.drawing/idrawingfactory/createlineargradientbrush/)(*RectangleF, IInterpolationColor[]*) | Создает кисть линейного градиента с указанными параметрами. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix)() | Создает новую единичную матрицу. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_1)(*[IMatrix](../imatrix/)*) | Создает новую матрицу с тем же содержимым, что и указанная матрица. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_2)(*float, float, float, float, float, float*) | Создает новую матрицу с указанными элементами. |
| [CreateSolidBrush](../../aspose.svg.drawing/idrawingfactory/createsolidbrush/)(*Color*) | Создает сплошную кисть с указанным цветом. |
| [CreateTextureBrush](../../aspose.svg.drawing/idrawingfactory/createtexturebrush/)(*byte[]*) | Создает текстурную кисть с указанными параметрами. |

### См. также

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
