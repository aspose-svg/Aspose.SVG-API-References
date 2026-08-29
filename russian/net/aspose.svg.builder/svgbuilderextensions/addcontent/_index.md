---
title: "SVGBuilderExtensions.AddContent"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddContent. Добавляет текстовое содержимое в SVG‑элемент."
type: docs
weight: 90
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addcontent/
---
## SVGBuilderExtensions.AddContent<TBuilder> method

Добавляет текстовое содержимое к элементу SVG.

```csharp
public static TBuilder AddContent<TBuilder>(this TBuilder builder, string text)
    where TBuilder : ISVGElementBuilder, ITextContentSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| текст | Текст, который будет добавлен к элементу. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

## Замечания

Этот метод позволяет добавлять текстовое содержимое напрямую в элемент SVG. Он полезен для элементов, содержащих текстовые данные.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentSetter](../../itextcontentsetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
