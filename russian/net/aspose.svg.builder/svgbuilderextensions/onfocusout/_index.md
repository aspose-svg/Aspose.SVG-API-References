---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions OnFocusOut. Устанавливает атрибут события onfocusout для обработки событий выхода фокуса на элементе"
type: docs
weight: 1460
url: /ru/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

Устанавливает атрибут события 'onfocusout' для обработки событий потери фокуса элементом.

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | JavaScript‑функция или скрипт, выполняемый, когда элемент теряет фокус, обычно до события 'onblur'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

## Замечания

'onfocusout' событие вызывается, когда элемент собирается потерять фокус. Аналогично 'onfocusin', это событие поддерживает всплытие и может использоваться для обнаружения изменений фокуса у дочерних элементов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
