---
title: "SVGBuilderExtensions.OnEmptied"
second_title: "Aspose.SVG для .NET справочник API"
description: "SVGBuilderExtensions OnEmptied метод. Устанавливает атрибут события onemptied для обработки опустошения источника медиа‑элемента."
type: docs
weight: 1400
url: /ru/net/aspose.svg.builder/svgbuilderextensions/onemptied/
---
## SVGBuilderExtensions.OnEmptied<TBuilder> method

Устанавливает атрибут события 'onemptied' для обработки очистки источника медиа‑элемента.

```csharp
public static TBuilder OnEmptied<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | JavaScript‑функция или скрипт, который будет выполнен, когда источник медиа‑элемента опустошён. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
