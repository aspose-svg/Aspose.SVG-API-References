---
title: "SVGBuilderExtensions.OnAbort"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions OnAbort. Устанавливает атрибут события onabort, определяющий скрипт, который будет выполнен при прерывании загрузки SVG‑документа."
type: docs
weight: 1190
url: /ru/net/aspose.svg.builder/svgbuilderextensions/onabort/
---
## SVGBuilderExtensions.OnAbort<TBuilder> method

Устанавливает атрибут события 'onabort', определяя скрипт, который будет выполнен при прерывании загрузки документа SVG.

```csharp
public static TBuilder OnAbort<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | JavaScript‑функция или скрипт, который будет выполнен при прерывании загрузки документа. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
