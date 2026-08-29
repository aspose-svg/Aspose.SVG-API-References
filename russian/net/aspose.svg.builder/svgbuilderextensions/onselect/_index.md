---
title: "SVGBuilderExtensions.OnSelect"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions OnSelect. Устанавливает атрибут события onselect для обработки событий выделения текста в элементе."
type: docs
weight: 1760
url: /ru/net/aspose.svg.builder/svgbuilderextensions/onselect/
---
## SVGBuilderExtensions.OnSelect<TBuilder> method

Устанавливает атрибут события 'onselect' для обработки событий выделения текста на элементе.

```csharp
public static TBuilder OnSelect<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | JavaScript‑функция или скрипт, который будет выполнен, когда в элементе выделяется текст. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
