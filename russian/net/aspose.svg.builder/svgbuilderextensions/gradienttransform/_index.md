---
title: "SVGBuilderExtensions.GradientTransform"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions GradientTransform. Устанавливает атрибут gradientTransform для элемента градиента."
type: docs
weight: 980
url: /ru/net/aspose.svg.builder/svgbuilderextensions/gradienttransform/
---
## SVGBuilderExtensions.GradientTransform<TBuilder> method

Устанавливает атрибут 'gradientTransform' для градиентного элемента.

```csharp
public static TBuilder GradientTransform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Конструктор SVG‑элементов, к которому применяется атрибут. |
| настроить | Функция для настройки конструктора трансформаций SVG. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
