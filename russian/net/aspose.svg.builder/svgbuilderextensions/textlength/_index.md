---
title: "SVGBuilderExtensions.TextLength"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions TextLength. Устанавливает точную длину текстового содержимого"
type: docs
weight: 2220
url: /ru/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

Устанавливает точную длину текстового содержимого.

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | Длина текста. |
| type | Тип единицы длины для значения. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

## Замечания

Этот метод устанавливает атрибут 'textLength', задавая желаемую длину текстового содержимого, потенциально переопределяя естественную длину текста.

### См. также

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
