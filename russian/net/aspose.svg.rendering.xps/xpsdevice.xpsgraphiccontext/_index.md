---
title: "XpsDevice.XpsGraphicContext класс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Rendering.Xps.XpsDeviceXpsGraphicContext класс. Содержит текущие параметры управления графикой для XpsDevice. Эти параметры определяют глобальную структуру, в которой выполняются графические операторы"
type: docs
weight: 5130
url: /ru/net/aspose.svg.rendering.xps/xpsdevice.xpsgraphiccontext/
---
## XpsDevice.XpsGraphicContext class

Содержит текущие параметры управления графикой для XpsDevice. Эти параметры определяют глобальную структуру, в которой выполняются графические операторы.

```csharp
public class XpsGraphicContext : GraphicContext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XpsGraphicContext](../../aspose.svg.rendering.xps/xpsdevice.xpsgraphiccontext/.ctor)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.svg.rendering/graphiccontext/characterspacing/) { get; set; } | Устанавливает или получает интервал между символами. |
| [CurrentElement](../../aspose.svg.rendering/graphiccontext/currentelement/) { get; } | Получает текущий обрабатываемый элемент. |
| virtual [FillBrush](../../aspose.svg.rendering/graphiccontext/fillbrush/) { get; set; } | Устанавливает или получает объект кисти, используемый для заполнения внутренних областей путей. |
| virtual [Font](../../aspose.svg.rendering/graphiccontext/font/) { get; set; } | Устанавливает или получает объект шрифта TrueType, используемый для рендеринга текста. |
| virtual [FontSize](../../aspose.svg.rendering/graphiccontext/fontsize/) { get; set; } | Устанавливает или получает размер шрифта текста. |
| virtual [FontStyle](../../aspose.svg.rendering/graphiccontext/fontstyle/) { get; set; } | Устанавливает или получает стиль шрифта текста. |
| virtual [LineCap](../../aspose.svg.rendering/graphiccontext/linecap/) { get; set; } | Устанавливает или получает код, определяющий форму конечных точек любого открытого пути, который обводится. |
| virtual [LineDashOffset](../../aspose.svg.rendering/graphiccontext/linedashoffset/) { get; set; } | Устанавливает или получает фазовый сдвиг текущего шаблона пунктирной линии. |
| virtual [LineDashPattern](../../aspose.svg.rendering/graphiccontext/linedashpattern/) { get; set; } | Устанавливает или получает описание шаблона пунктиров, используемого при обводке путей. Может быть установлено в `null` или пустой массив для отключения. |
| virtual [LineJoin](../../aspose.svg.rendering/graphiccontext/linejoin/) { get; set; } | Устанавливает или получает код, определяющий форму соединений между связанными сегментами обводимого пути. |
| virtual [LineWidth](../../aspose.svg.rendering/graphiccontext/linewidth/) { get; set; } | Устанавливает или получает толщину путей, которые будут обведены. |
| virtual [MiterLimit](../../aspose.svg.rendering/graphiccontext/miterlimit/) { get; set; } | Устанавливает или получает максимальную длину срезов (mitered) соединений линий для обведенных путей. Этот параметр ограничивает длину «шипов», образующихся, когда сегменты линий соединяются под острыми углами. |
| virtual [StrokeBrush](../../aspose.svg.rendering/graphiccontext/strokebrush/) { get; set; } | Устанавливает или получает объект кисти, который используется для обведенных путей. |
| virtual [TextInfo](../../aspose.svg.rendering/graphiccontext/textinfo/) { get; } | Получает объект [`TextInfo`](../../aspose.svg.rendering/textinfo/), который содержит информацию о отрисованном тексте. |
| virtual [TransformationMatrix](../../aspose.svg.rendering/graphiccontext/transformationmatrix/) { get; set; } | Устанавливает или получает матрицу преобразования. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.svg.rendering/graphiccontext/clone/)() | Создаёт новый экземпляр класса **GraphicContext** с теми же значениями свойств, что и у существующего экземпляра. |
| virtual [Transform](../../aspose.svg.rendering/graphiccontext/transform/)(*[IMatrix](../../aspose.svg.drawing/imatrix/)*) | Изменяет текущую матрицу преобразования, умножая её на указанную матрицу. |

### См. также

* class [GraphicContext](../../aspose.svg.rendering/graphiccontext/)
* class [XpsDevice](../xpsdevice/)
* namespace [Aspose.Svg.Rendering.Xps](../../aspose.svg.rendering.xps/)
* assembly [Aspose.SVG](../../)
