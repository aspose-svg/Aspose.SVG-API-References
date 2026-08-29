---
title: "SVGBuilderExtensions.Transform"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions Transform. Устанавливает атрибут transform для SVG‑элемента"
type: docs
weight: 2260
url: /ru/net/aspose.svg.builder/svgbuilderextensions/transform/
---
## SVGBuilderExtensions.Transform<TBuilder> method

Устанавливает атрибут 'transform' для SVG‑элемента.

```csharp
public static TBuilder Transform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, ITransformAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Функция для настройки трансформации SVG. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransformAttributeSetter](../../itransformattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
