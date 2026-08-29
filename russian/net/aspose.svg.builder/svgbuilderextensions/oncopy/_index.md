---
title: "SVGBuilderExtensions.OnCopy"
second_title: "Aspose.SVG для .NET справочник API"
description: "SVGBuilderExtensions OnCopy метод. Устанавливает атрибут события oncopy, определяющий скрипт, который будет выполнен при копировании содержимого из элемента SVG."
type: docs
weight: 1270
url: /ru/net/aspose.svg.builder/svgbuilderextensions/oncopy/
---
## SVGBuilderExtensions.OnCopy<TBuilder> method

Устанавливает атрибут события 'oncopy', определяя скрипт, который будет выполнен при копировании содержимого из SVG‑элемента.

```csharp
public static TBuilder OnCopy<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | JavaScript‑функция или скрипт, который будет выполнен при событии копирования. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
