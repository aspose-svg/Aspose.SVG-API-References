---
title: "SVGBuilderExtensions.OnCut"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions OnCut. Устанавливает атрибут события oncut, определяющий скрипт, который будет выполнен при вырезании содержимого из SVG‑элемента."
type: docs
weight: 1290
url: /ru/net/aspose.svg.builder/svgbuilderextensions/oncut/
---
## SVGBuilderExtensions.OnCut<TBuilder> method

Устанавливает атрибут события 'oncut', определяя скрипт, который будет выполнен при вырезании содержимого из SVG‑элемента.

```csharp
public static TBuilder OnCut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | JavaScript‑функция или скрипт, который будет выполнен при событии cut. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
