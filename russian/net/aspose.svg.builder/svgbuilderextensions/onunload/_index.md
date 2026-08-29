---
title: "SVGBuilderExtensions.OnUnload"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions OnUnload. Устанавливает атрибут события onunload, определяющий скрипт, который будет выполнен при выгрузке SVG‑документа."
type: docs
weight: 1830
url: /ru/net/aspose.svg.builder/svgbuilderextensions/onunload/
---
## SVGBuilderExtensions.OnUnload<TBuilder> method

Устанавливает атрибут события 'onunload', определяя скрипт, который будет выполнен при выгрузке SVG‑документа.

```csharp
public static TBuilder OnUnload<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | JavaScript‑функция или скрипт, который будет выполнен при выгрузке документа. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
