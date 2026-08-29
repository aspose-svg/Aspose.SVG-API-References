---
title: "SVGBuilderExtensions.Points"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions Points. Устанавливает атрибут points для SVG‑элемента, используя массив значений double."
type: docs
weight: 1910
url: /ru/net/aspose.svg.builder/svgbuilderextensions/points/
---
## Points<TBuilder>(*this TBuilder, params double[]*) {#points}

Устанавливает атрибут 'points' для SVG‑элемента, используя массив чисел с плавающей запятой.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params double[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| точки | Массив значений double, представляющих точки (должен содержать чётное количество элементов). |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, если предоставлено нечётное количество точек. |

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Points<TBuilder>(*this TBuilder, params PointF[]*) {#points_1}

Устанавливает атрибут 'points' для SVG‑элемента, используя массив объектов PointF.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params PointF[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| точки | Массив объектов PointF, представляющих точки. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
