---
title: "SVGBuilderExtensions.FillOpacity"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions FillOpacity. Устанавливает атрибут fill-opacity для SVG‑элемента. Значение должно быть от 0.0 (полностью прозрачно) до 1.0 (полностью непрозрачно)."
type: docs
weight: 820
url: /ru/net/aspose.svg.builder/svgbuilderextensions/fillopacity/
---
## SVGBuilderExtensions.FillOpacity<TBuilder> method

Устанавливает атрибут 'fill-opacity' для SVG‑элемента. Значение должно быть между 0.0 (полностью прозрачное) и 1.0 (полностью непрозрачное).

```csharp
public static TBuilder FillOpacity<TBuilder>(this TBuilder builder, double opacity)
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
