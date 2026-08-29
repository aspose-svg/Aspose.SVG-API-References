---
title: "SVGBuilderExtensions.KeySplines"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions KeySplines. Устанавливает атрибут keySplines, определяющий контрольные точки для темпа анимации"
type: docs
weight: 1060
url: /ru/net/aspose.svg.builder/svgbuilderextensions/keysplines/
---
## SVGBuilderExtensions.KeySplines<TBuilder> method

Устанавливает атрибут 'keySplines', указывая контрольные точки для темпа анимации.

```csharp
public static TBuilder KeySplines<TBuilder>(this TBuilder builder, 
    Action<AnimationSplineBuilder> buildSplines)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| buildSplines | Действие для построения конфигурации сплайна. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [AnimationSplineBuilder](../../animationsplinebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
