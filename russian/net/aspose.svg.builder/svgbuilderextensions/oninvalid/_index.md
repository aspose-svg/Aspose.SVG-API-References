---
title: "SVGBuilderExtensions.OnInvalid"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions OnInvalid. Устанавливает атрибут события oninvalid для обработки недопустимых событий в элементах формы"
type: docs
weight: 1480
url: /ru/net/aspose.svg.builder/svgbuilderextensions/oninvalid/
---
## SVGBuilderExtensions.OnInvalid<TBuilder> method

Устанавливает атрибут события 'oninvalid' для обработки недействительных событий в элементах формы.

```csharp
public static TBuilder OnInvalid<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | JavaScript‑функция или скрипт, который будет выполнен, когда значение элемента недействительно. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
