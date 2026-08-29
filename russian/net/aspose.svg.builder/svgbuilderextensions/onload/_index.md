---
title: "SVGBuilderExtensions.OnLoad"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions OnLoad. Устанавливает атрибут события onload для обработки событий загрузки элемента"
type: docs
weight: 1520
url: /ru/net/aspose.svg.builder/svgbuilderextensions/onload/
---
## SVGBuilderExtensions.OnLoad<TBuilder> method

Устанавливает атрибут события 'onload' для обработки событий загрузки на элементе.

```csharp
public static TBuilder OnLoad<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | JavaScript‑функция или скрипт, который будет выполнен после завершения загрузки элемента. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
