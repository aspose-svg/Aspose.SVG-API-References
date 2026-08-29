---
title: "DeviceTGraphicContextTRenderingOptions Класс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Rendering.Device2TGraphicContextTRenderingOptions класс. Представляет базовый класс для реализации конкретных устройств рендеринга"
type: docs
weight: 4820
url: /ru/net/aspose.svg.rendering/device-2/
---
## Device<TGraphicContext,TRenderingOptions> class

Представляет базовый класс для реализации конкретных рендеринговых устройств.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Параметр | Описание |
| --- | --- |
| TGraphicContext | Графический контекст, содержащий текущие параметры управления графикой |
| TRenderingOptions | Параметры рендеринга |

## Свойства

| Имя | Описание |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } | Получает графический контекст |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } | Получает параметры отрисовки. |
| virtual [Configuration](../../aspose.svg.rendering/device-2/configuration/) { get; } | Получает конфигурацию устройства. |
| [OutputStream](../../aspose.svg.rendering/device-2/outputstream/) { get; } | Устанавливает и получает выходной поток. |
| [StreamProvider](../../aspose.svg.rendering/device-2/streamprovider/) { get; } | Получает объект поставщика потока. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [AddRect](../../aspose.svg.rendering/device-2/addrect/)(*RectangleF*) | Добавляет прямоугольник к текущему пути как отдельный подпуть. |
| virtual [BeginDocument](../../aspose.svg.rendering/device-2/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | Начинает отрисовку документа. |
| virtual [BeginElement](../../aspose.svg.rendering/device-2/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | Начинает отрисовку узла. |
| virtual [BeginPage](../../aspose.svg.rendering/device-2/beginpage/)(*SizeF*) | Начинает отрисовку новой страницы. |
| virtual [Clip](../../aspose.svg.rendering/device-2/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Изменяет текущий путь отсечения, пересекает его с текущим путем, используя FillRule для определения области заполнения. Этот метод завершает текущий путь. |
| virtual [ClosePath](../../aspose.svg.rendering/device-2/closepath/)() | Закрывает текущий подпуть, добавляя прямой отрезок от текущей точки до начальной точки подпути. Если текущий подпуть уже закрыт, \"ClosePath\" ничего не делает. Этот оператор завершает текущий подпуть. Добавление другого отрезка к текущему пути начинает новый подпуть, даже если новый отрезок начинается в конечной точке, достигнутой методом \"ClosePath\". |
| virtual [CubicBezierTo](../../aspose.svg.rendering/device-2/cubicbezierto/)(*PointF, PointF, PointF*) | Добавляет кубическую кривую Bézier к текущему пути. Кривая проходит от текущей точки к точке pt2, используя pt1 и pt2 в качестве контрольных точек Bézier. Новая текущая точка — pt3. |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| virtual [DrawImage](../../aspose.svg.rendering/device-2/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | Отрисовывает указанное изображение. |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() | Завершает отрисовку документа. |
| virtual [EndElement](../../aspose.svg.rendering/device-2/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | Завершает отрисовку узла. |
| virtual [EndPage](../../aspose.svg.rendering/device-2/endpage/)() | Завершает отрисовку текущей страницы. |
| virtual [Fill](../../aspose.svg.rendering/device-2/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Заполняет всю область, ограниченную текущим путем. Если путь состоит из нескольких несвязанных подпутей, он заполняет внутренние части всех подпутей совместно. Этот метод завершает текущий путь. |
| virtual [FillText](../../aspose.svg.rendering/device-2/filltext/)(*string, PointF*) | Заполняет указанную строку текста в указанном месте. |
| virtual [Flush](../../aspose.svg.rendering/device-2/flush/)() | Сбрасывает все данные в поток вывода. |
| virtual [LineTo](../../aspose.svg.rendering/device-2/lineto/)(*PointF*) | Добавляет прямой отрезок линии от текущей точки к точке (pt). Новая текущая точка — pt. |
| virtual [MoveTo](../../aspose.svg.rendering/device-2/moveto/)(*PointF*) | Начинает новый подпуть, перемещая текущую точку к координатам параметра pt, без создания соединяющего отрезка. Если предыдущий метод построения пути в текущем пути также был "MoveTo", новый "MoveTo" переопределяет его; никаких следов предыдущей операции "MoveTo" в пути не остаётся. |
| virtual [RestoreGraphicContext](../../aspose.svg.rendering/device-2/restoregraphiccontext/)() | Восстанавливает весь графический контекст до его прежнего значения, извлекая его из стека. |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() | Помещает копию всего графического контекста в стек. |
| virtual [Stroke](../../aspose.svg.rendering/device-2/stroke/)() | Обводит линию вдоль текущего пути. Обводимая линия следует каждому прямому или изогнутому сегменту пути, центрируясь на сегменте со сторонами, параллельными ему. Каждый подпуть пути обрабатывается отдельно. Этот метод завершает текущий путь. |
| virtual [StrokeAndFill](../../aspose.svg.rendering/device-2/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Обводит и заполняет текущий путь. Этот метод завершает текущий путь. |
| virtual [StrokeText](../../aspose.svg.rendering/device-2/stroketext/)(*string, PointF*) | Обводит указанный текст в заданном месте. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [DeviceConfiguration<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.deviceconfiguration-2) | Представляет объект конфигурации для устройств. |
| enum [PageWritingStrategy<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.pagewritingstrategy-2) | Указывает типы стратегий для записи страниц в поток\потоки вывода. |

### См. также

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
