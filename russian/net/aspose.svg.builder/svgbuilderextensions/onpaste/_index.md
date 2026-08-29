---
title: "SVGBuilderExtensions.OnPaste"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions OnPaste. Устанавливает атрибут события onpaste, определяющий скрипт, который будет выполнен при вставке содержимого в элемент SVG."
type: docs
weight: 1640
url: /ru/net/aspose.svg.builder/svgbuilderextensions/onpaste/
---
## SVGBuilderExtensions.OnPaste<TBuilder> method

Устанавливает атрибут события 'onpaste', определяя скрипт, который будет выполнен при вставке содержимого в SVG‑элемент.

```csharp
public static TBuilder OnPaste<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | JavaScript‑функция или скрипт, который будет выполнен при событии вставки. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
