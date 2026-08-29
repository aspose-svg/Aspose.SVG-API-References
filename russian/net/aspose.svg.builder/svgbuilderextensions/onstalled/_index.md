---
title: "SVGBuilderExtensions.OnStalled"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions OnStalled. Устанавливает атрибут события onstalled для обработки событий, когда передача медиа‑данных неожиданно останавливается."
type: docs
weight: 1780
url: /ru/net/aspose.svg.builder/svgbuilderextensions/onstalled/
---
## SVGBuilderExtensions.OnStalled<TBuilder> method

Устанавливает атрибут события 'onstalled' для обработки событий, когда передача данных медиа неожиданно останавливается.

```csharp
public static TBuilder OnStalled<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | JavaScript‑функция или скрипт, который будет выполнен, когда передача медиа‑данных останавливается. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
