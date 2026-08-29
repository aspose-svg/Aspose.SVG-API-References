---
title: "SVGBuilderExtensions.Width"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions Width. Устанавливает атрибут width для SVG‑элемента"
type: docs
weight: 2330
url: /ru/net/aspose.svg.builder/svgbuilderextensions/width/
---
## SVGBuilderExtensions.Width<TBuilder> method

Устанавливает атрибут 'width' для SVG‑элемента.

```csharp
public static TBuilder Width<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IWidthAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| значение | Значение атрибута 'width'. |
| type | Тип измерения длины (по умолчанию — пиксели). |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IWidthAttributeSetter](../../iwidthattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
