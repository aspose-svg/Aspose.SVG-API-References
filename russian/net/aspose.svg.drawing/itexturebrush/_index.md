---
title: ITextureBrush
second_title: Справочник по Aspose.SVG для .NET API
description: Определяет интерфейс кисти который использует изображение для заполнения внутренней части фигуры.
type: docs
weight: 1480
url: /ru/net/aspose.svg.drawing/itexturebrush/
---
## ITextureBrush interface

Определяет интерфейс кисти, который использует изображение для заполнения внутренней части фигуры.

```csharp
public interface ITextureBrush : ITransformableBrush
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ColorMap](../../aspose.svg.drawing/itexturebrush/colormap) { get; } | Количество элементов должно быть четным. Каждый четный элемент имеет старый цвет. Каждый нечетный элемент — новый цвет. |
| [Image](../../aspose.svg.drawing/itexturebrush/image) { get; } | Получает или задает изображение, используемое кистью. |
| [ImageArea](../../aspose.svg.drawing/itexturebrush/imagearea) { get; } | Определяет часть изображения, используемую кистью. Если равно RectangleF.Empty, то будет использовано все изображение. Координаты в пикселях. |
| [Opacity](../../aspose.svg.drawing/itexturebrush/opacity) { get; } | Получить значение непрозрачности в матрице преобразования цвета. |

### Смотрите также

* interface [ITransformableBrush](../itransformablebrush)
* пространство имен [Aspose.Svg.Drawing](../../aspose.svg.drawing)
* сборка [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
