---
title: "SVGBuilderExtensions.Rect"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions Rect. Устанавливает атрибуты x, y, width и height для SVG‑элемента, определяющего прямоугольник"
type: docs
weight: 1920
url: /ru/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

Устанавливает атрибуты 'x', 'y', 'width' и 'height' для SVG‑элемента, определяя прямоугольник.

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| x | Координата x прямоугольника. |
| y | Координата y прямоугольника. |
| width | Ширина прямоугольника. |
| height | Высота прямоугольника. |
| type | Тип измерения длины для всех размеров (по умолчанию — пиксели). |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
