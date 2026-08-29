---
title: "SVGBuilderExtensions.Height"
second_title: "Aspose.SVG для .NET справочник API"
description: "SVGBuilderExtensions Height метод. Устанавливает атрибут height для SVG‑элемента."
type: docs
weight: 1000
url: /ru/net/aspose.svg.builder/svgbuilderextensions/height/
---
## SVGBuilderExtensions.Height<TBuilder> method

Устанавливает атрибут 'height' для элемента SVG.

```csharp
public static TBuilder Height<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IHeightAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| значение | Значение атрибута 'height'. |
| type | Тип измерения длины (по умолчанию — пиксели). |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IHeightAttributeSetter](../../iheightattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
