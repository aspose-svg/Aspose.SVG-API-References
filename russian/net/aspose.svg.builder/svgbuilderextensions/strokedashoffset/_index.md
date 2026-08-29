---
title: "SVGBuilderExtensions.StrokeDashoffset"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions StrokeDashoffset. Устанавливает атрибут stroke-dashoffset для SVG‑элемента, определяющий смещение начала массива штрихов линии."
type: docs
weight: 2100
url: /ru/net/aspose.svg.builder/svgbuilderextensions/strokedashoffset/
---
## SVGBuilderExtensions.StrokeDashoffset<TBuilder> method

Устанавливает атрибут 'stroke-dashoffset' для SVG‑элемента, определяя смещение начала массива штрихов контура.

```csharp
public static TBuilder StrokeDashoffset<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| значение | Значение смещения штриха. |
| type | Тип единицы измерения для значения смещения. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
