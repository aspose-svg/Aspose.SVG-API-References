---
title: "Интерфейс IDevice"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Rendering.IDevice. Определяет методы и свойства, поддерживающие пользовательскую отрисовку графических элементов, таких как пути, текст и изображения."
type: docs
weight: 4890
url: /ru/net/aspose.svg.rendering/idevice/
---
## IDevice interface

Определяет методы и свойства, поддерживающие пользовательский рендеринг графических элементов, таких как пути, текст и изображения.

```csharp
public interface IDevice : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/idevice/graphiccontext/) { get; } | Получает графический контекст. |
| [Options](../../aspose.svg.rendering/idevice/options/) { get; } | Получает параметры отрисовки. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddRect](../../aspose.svg.rendering/idevice/addrect/)(*RectangleF*) | Добавляет прямоугольник к текущему пути как отдельный подпуть. |
| [BeginDocument](../../aspose.svg.rendering/idevice/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | Начинает отрисовку документа. |
| [BeginElement](../../aspose.svg.rendering/idevice/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | Начинает отрисовку элемента. |
| [BeginPage](../../aspose.svg.rendering/idevice/beginpage/)(*SizeF*) | Начинает отрисовку новой страницы. |
| [Clip](../../aspose.svg.rendering/idevice/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Изменяет текущий путь отсечения, пересекает его с текущим путем, используя FillRule для определения области заполнения. Этот метод завершает текущий путь. |
| [ClosePath](../../aspose.svg.rendering/idevice/closepath/)() | Закрывает текущий подпуть, добавляя прямой отрезок от текущей точки до начальной точки подпути. Если текущий подпуть уже закрыт, \"ClosePath\" ничего не делает. Этот оператор завершает текущий подпуть. Добавление другого отрезка к текущему пути начинает новый подпуть, даже если новый отрезок начинается в конечной точке, достигнутой методом \"ClosePath\". |
| [CubicBezierTo](../../aspose.svg.rendering/idevice/cubicbezierto/)(*PointF, PointF, PointF*) | Добавляет кубическую кривую Безье к текущему пути. Кривая проходит от текущей точки к точке pt3, используя pt1 и pt2 в качестве контрольных точек Безье. Новая текущая точка — pt3. |
| [DrawImage](../../aspose.svg.rendering/idevice/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | Отрисовывает указанное изображение. |
| [EndDocument](../../aspose.svg.rendering/idevice/enddocument/)() | Завершает отрисовку документа. |
| [EndElement](../../aspose.svg.rendering/idevice/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | Завершает отрисовку элемента. |
| [EndPage](../../aspose.svg.rendering/idevice/endpage/)() | Завершает отрисовку текущей страницы. |
| [Fill](../../aspose.svg.rendering/idevice/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Заполняет всю область, ограниченную текущим путем. Если путь состоит из нескольких несвязанных подпутей, он заполняет внутренние части всех подпутей совместно. Этот метод завершает текущий путь. |
| [FillText](../../aspose.svg.rendering/idevice/filltext/)(*string, PointF*) | Заполняет указанную строку текста в указанном месте. |
| [Flush](../../aspose.svg.rendering/idevice/flush/)() | Сбрасывает все данные в поток вывода. |
| [LineTo](../../aspose.svg.rendering/idevice/lineto/)(*PointF*) | Добавляет прямой отрезок линии от текущей точки к точке (pt). Новая текущая точка — pt. |
| [MoveTo](../../aspose.svg.rendering/idevice/moveto/)(*PointF*) | Начинает новый подпуть, перемещая текущую точку к координатам параметра pt, без создания соединяющего отрезка. Если предыдущий метод построения пути в текущем пути также был "MoveTo", новый "MoveTo" переопределяет его; никаких следов предыдущей операции "MoveTo" в пути не остаётся. |
| [RestoreGraphicContext](../../aspose.svg.rendering/idevice/restoregraphiccontext/)() | Восстанавливает весь графический контекст до его прежнего значения, извлекая его из стека. |
| [SaveGraphicContext](../../aspose.svg.rendering/idevice/savegraphiccontext/)() | Помещает копию всего графического контекста в стек. |
| [Stroke](../../aspose.svg.rendering/idevice/stroke/)() | Обводит линию вдоль текущего пути. Обводимая линия следует каждому прямому или изогнутому сегменту пути, центрируясь на сегменте со сторонами, параллельными ему. Каждый подпуть пути обрабатывается отдельно. Этот метод завершает текущий путь. |
| [StrokeAndFill](../../aspose.svg.rendering/idevice/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Обводит и заполняет текущий путь. Этот метод завершает текущий путь. |
| [StrokeText](../../aspose.svg.rendering/idevice/stroketext/)(*string, PointF*) | Обводит указанный текст в заданном месте. |

### См. также

* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
