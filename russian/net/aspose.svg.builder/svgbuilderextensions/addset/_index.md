---
title: "SVGBuilderExtensions.AddSet"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddSet. Добавляет конфигурацию элемента set в построитель"
type: docs
weight: 470
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addset/
---
## SVGBuilderExtensions.AddSet<TBuilder> method

Добавляет конфигурацию элемента 'set' в построитель.

```csharp
public static TBuilder AddSet<TBuilder>(this TBuilder builder, 
    Action<SVGSetElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IBaseAnimationElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'set'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGSetElementBuilder](../../svgsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IBaseAnimationElementBuilder](../../ibaseanimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
