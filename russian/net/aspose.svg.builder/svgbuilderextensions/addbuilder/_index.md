---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddBuilder. Добавляет существующий SVG‑builder к текущему SVG‑builder. Этот метод используется для включения предопределённого SVG‑builder в текущий builder."
type: docs
weight: 60
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

Добавляет существующий построитель SVG‑элемента в текущий построитель SVG‑элемента. Этот метод используется для включения заранее определённого построителя SVG‑элемента в текущий построитель.

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| TElementBuilder | Тип SVG‑builder, который необходимо настроить. TElementBuilder должен реализовывать ISVGElementBuilder. |
| билдер | SVG‑builder, к которому добавляется другой элемент‑builder. |
| elementBuilder | Конструктор SVG‑элемента, который будет добавлен. |

### Возвращаемое значение

Исходный построитель элемента SVG для цепочки вызовов методов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
