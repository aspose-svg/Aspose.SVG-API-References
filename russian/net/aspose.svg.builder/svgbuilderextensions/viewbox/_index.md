---
title: "SVGBuilderExtensions.ViewBox"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions ViewBox. Устанавливает атрибут viewBox для SVG‑элемента"
type: docs
weight: 2300
url: /ru/net/aspose.svg.builder/svgbuilderextensions/viewbox/
---
## SVGBuilderExtensions.ViewBox<TBuilder> method

Устанавливает атрибут 'viewBox' для SVG‑элемента.

```csharp
public static TBuilder ViewBox<TBuilder>(this TBuilder builder, double minX, double minY, 
    double width, double height)
    where TBuilder : ISVGElementBuilder, IViewBoxAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| minX | Минимальная координата X viewBox. |
| minY | Минимальная координата Y viewBox. |
| width | Ширина viewBox. |
| height | Высота viewBox. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IViewBoxAttributeSetter](../../iviewboxattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
