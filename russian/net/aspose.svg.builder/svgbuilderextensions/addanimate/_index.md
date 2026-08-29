---
title: "SVGBuilderExtensions.AddAnimate"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddAnimate. Добавляет конфигурацию элемента animate в построитель."
type: docs
weight: 30
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addanimate/
---
## SVGBuilderExtensions.AddAnimate<TBuilder> method

Добавляет конфигурацию элемента 'animate' в построитель.

```csharp
public static TBuilder AddAnimate<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IBaseAnimationElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'animate'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGAnimateElementBuilder](../../svganimateelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IBaseAnimationElementBuilder](../../ibaseanimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
