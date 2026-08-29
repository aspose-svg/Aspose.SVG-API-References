---
title: "SVGBuilderExtensions.End"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод End класса SVGBuilderExtensions. Устанавливает атрибут end, определяющий, когда анимация должна завершиться."
type: docs
weight: 790
url: /ru/net/aspose.svg.builder/svgbuilderextensions/end/
---
## SVGBuilderExtensions.End<TBuilder> method

Устанавливает атрибут 'end', определяя, когда анимация должна завершиться.

```csharp
public static TBuilder End<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
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
