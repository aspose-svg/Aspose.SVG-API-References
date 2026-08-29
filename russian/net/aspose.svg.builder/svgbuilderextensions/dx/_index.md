---
title: "SVGBuilderExtensions.Dx"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions Dx. Устанавливает атрибут dx для корректировки горизонтального положения каждого символа в тексте."
type: docs
weight: 770
url: /ru/net/aspose.svg.builder/svgbuilderextensions/dx/
---
## Dx<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#dx}

Устанавливает атрибут 'dx' для корректировки горизонтального положения каждого символа в тексте.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| type | Тип единицы длины для значений. |
| значения | Значения горизонтальной коррекции для каждого символа. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

## Замечания

Этот метод позволяет точно управлять горизонтальным интервалом между символами в тексте.

### См. также

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dx<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dx_1}

Устанавливает одно значение горизонтального смещения для текстового содержимого.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | Значение горизонтальной коррекции. |
| type | Тип единицы длины для значения. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

## Замечания

Этот метод устанавливает атрибут 'dx' одним значением, корректируя горизонтальное положение текстового содержимого.

### См. также

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
