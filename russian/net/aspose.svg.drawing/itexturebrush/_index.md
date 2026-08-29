---
title: "Интерфейс ITextureBrush"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Drawing.ITextureBrush. Определяет интерфейс кисти, использующей изображение для заполнения внутренней части фигуры"
type: docs
weight: 3520
url: /ru/net/aspose.svg.drawing/itexturebrush/
---
## ITextureBrush interface

Определяет интерфейс кисти, использующей изображение для заполнения внутренней части фигуры.

```csharp
public interface ITextureBrush : ITransformableBrush
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ColorMap](../../aspose.svg.drawing/itexturebrush/colormap/) { get; } | Количество элементов должно быть четным. Каждый четный элемент — старый цвет. Каждый нечетный элемент — новый цвет. |
| [Image](../../aspose.svg.drawing/itexturebrush/image/) { get; } | Получает или задает изображение, используемое кистью. |
| [ImageArea](../../aspose.svg.drawing/itexturebrush/imagearea/) { get; } | Указывает часть изображения, используемую кистью. Если она равна RectangleF.Empty, будет использовано всё изображение. Координаты указаны в пикселях. |
| [Opacity](../../aspose.svg.drawing/itexturebrush/opacity/) { get; set; } | Получить значение непрозрачности в матрице цветового преобразования. |

### См. также

* interface [ITransformableBrush](../itransformablebrush/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
