---
title: "SVGBuilderExtensions.Y"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions Y. Устанавливает атрибут y для SVG‑элемента"
type: docs
weight: 2400
url: /ru/net/aspose.svg.builder/svgbuilderextensions/y/
---
## Y<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#y_1}

Устанавливает атрибут 'y' для элемента SVG.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IYAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| значение | Значение атрибута 'y'. |
| type | Тип измерения длины (по умолчанию — пиксели). |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IYAttributeSetter](../../iyattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Y<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#y}

Устанавливает атрибут 'y' для позиционирования текстового содержимого вдоль оси y.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| type | Тип единицы длины для значений. |
| значения | Значения позиции по оси y. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

## Замечания

Этот метод устанавливает атрибут 'y', который определяет вертикальное положение(я) текстового элемента.

### См. также

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
