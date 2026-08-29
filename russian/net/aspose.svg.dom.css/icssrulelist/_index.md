---
title: "Интерфейс ICSSRuleList"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Dom.Css.ICSSRuleList. Интерфейс CSSRuleList предоставляет абстракцию упорядоченной коллекции правил CSS."
type: docs
weight: 2630
url: /ru/net/aspose.svg.dom.css/icssrulelist/
---
## ICSSRuleList interface

Интерфейс CSSRuleList предоставляет абстракцию упорядоченной коллекции правил CSS.

```csharp
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.svg.dom.css/icssrulelist/item/) { get; } | Используется для получения правила CSS методом item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). Порядок в этой коллекции соответствует порядку правил в таблице стилей CSS. Если индекс больше или равен количеству правил в списке, возвращается null. |
| [Length](../../aspose.svg.dom.css/icssrulelist/length/) { get; } | Количество CSS‑правил в списке. Диапазон допустимых индексов дочерних правил — от 0 до length‑1 включительно. |

### См. также

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
