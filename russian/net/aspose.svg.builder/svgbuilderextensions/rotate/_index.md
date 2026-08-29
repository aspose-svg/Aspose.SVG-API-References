---
title: "SVGBuilderExtensions.Rotate"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions Rotate. Устанавливает углы вращения для отдельных символов или сегментов текстового содержимого."
type: docs
weight: 2000
url: /ru/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

Устанавливает углы вращения для отдельных символов или сегментов текстового содержимого.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значения | Массив углов вращения в градусах. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

## Замечания

Этот метод задает атрибут 'rotate' с несколькими значениями, позволяя выполнять индивидуальное вращение каждого символа или текстового сегмента.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

Устанавливает единый угол вращения для всего текстового содержимого.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | Угол вращения в градусах. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

## Замечания

Этот метод задает атрибут 'rotate' одним значением, применяя одинаковый угол вращения ко всему текстовому содержимому.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
