---
title: "SVGBuilderExtensions.Begin"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions Begin. Устанавливает атрибут begin, определяющий, когда должна начаться анимация"
type: docs
weight: 610
url: /ru/net/aspose.svg.builder/svgbuilderextensions/begin/
---
## SVGBuilderExtensions.Begin<TBuilder> method

Устанавливает атрибут 'begin', определяя, когда должна начаться анимация.

```csharp
public static TBuilder Begin<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| настроить | Делегат для настройки значения времени. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [TimingValueBuilder](../../timingvaluebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
