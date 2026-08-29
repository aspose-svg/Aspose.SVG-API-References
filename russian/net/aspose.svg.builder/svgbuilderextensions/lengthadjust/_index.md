---
title: "SVGBuilderExtensions.LengthAdjust"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions LengthAdjust. Устанавливает метод корректировки длины для текстового содержимого."
type: docs
weight: 1090
url: /ru/net/aspose.svg.builder/svgbuilderextensions/lengthadjust/
---
## SVGBuilderExtensions.LengthAdjust<TBuilder> method

Устанавливает метод коррекции длины для текстового содержимого.

```csharp
public static TBuilder LengthAdjust<TBuilder>(this TBuilder builder, LengthAdjust value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | Метод корректировки длины. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

## Замечания

Этот метод устанавливает атрибут 'lengthAdjust', определяя, как корректируется длина текста — либо за счёт интервалов, либо за счёт масштабирования.

### См. также

* enum [LengthAdjust](../../lengthadjust/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
