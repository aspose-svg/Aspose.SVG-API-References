---
title: "SVGBuilderExtensions.OnToggle"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод OnToggle в SVGBuilderExtensions. Устанавливает атрибут события ontoggle для обработки событий, когда пользователь переключает элемент управления, например, details."
type: docs
weight: 1820
url: /ru/net/aspose.svg.builder/svgbuilderextensions/ontoggle/
---
## SVGBuilderExtensions.OnToggle<TBuilder> method

Устанавливает атрибут события 'ontoggle' для обработки событий, когда пользователь переключает элемент управления, например элемент `details`.

```csharp
public static TBuilder OnToggle<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | JavaScript‑функция или скрипт, который будет выполнен при переключении элемента управления. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
