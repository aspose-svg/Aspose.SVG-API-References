---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions OnFocusIn. Устанавливает атрибут события onfocusin для обработки событий получения фокуса элементом."
type: docs
weight: 1450
url: /ru/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

Устанавливает атрибут события 'onfocusin' для обработки событий получения фокуса элементом.

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | JavaScript‑функция или скрипт, выполняемый, когда элемент получает фокус, обычно до события 'onfocus'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

## Замечания

Событие 'onfocusin' срабатывает, когда элемент собирается получить фокус. Это событие отличается от 'onfocus' тем, что поддерживает всплытие и может использоваться для обнаружения изменений фокуса у дочерних элементов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
