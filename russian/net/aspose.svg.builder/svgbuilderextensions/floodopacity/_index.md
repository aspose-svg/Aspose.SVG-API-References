---
title: "SVGBuilderExtensions.FloodOpacity"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions FloodOpacity. Устанавливает атрибут flood-opacity для SVG‑элемента. Значение должно быть в диапазоне от 0.0 полностью прозрачного до 1.0 полностью непрозрачного."
type: docs
weight: 860
url: /ru/net/aspose.svg.builder/svgbuilderextensions/floodopacity/
---
## SVGBuilderExtensions.FloodOpacity<TBuilder> method

Устанавливает атрибут 'flood-opacity' для элемента SVG. Значение должно быть в диапазоне от 0.0 (полностью прозрачный) до 1.0 (полностью непрозрачный).

```csharp
public static TBuilder FloodOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| непрозрачность | Значение непрозрачности для установки. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Выбрасывается, если значение непрозрачности находится вне допустимого диапазона. |

### См. также

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
