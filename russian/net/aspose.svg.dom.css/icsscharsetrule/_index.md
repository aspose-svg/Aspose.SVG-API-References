---
title: "ICSSCharsetRule Interface"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Css.ICSSCharsetRule interface. Интерфейс CSSCharsetRule представляет правило набора символов в таблице стилей CSS. Значение атрибута encoding не влияет на кодировку текстовых данных в объектах DOM, эта кодировка всегда UTF-16. После загрузки таблицы стилей значение атрибута encoding равно значению, найденному в правиле charset. Если в исходном документе не было charset, то CSSCharsetRule не создаётся. Значение атрибута encoding также может использоваться как подсказка для кодировки, используемой при сериализации таблицы стилей."
type: docs
weight: 2530
url: /ru/net/aspose.svg.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

Интерфейс CSSCharsetRule представляет правило @charset в таблице стилей CSS. Значение атрибута encoding не влияет на кодировку текстовых данных в объектах DOM; эта кодировка всегда UTF-16. После загрузки таблицы стилей значение атрибута encoding равно значению, найденному в правиле @charset. Если в оригинальном документе не было @charset, то CSSCharsetRule не создаётся. Значение атрибута encoding также может использоваться как подсказка для кодировки, применяемой при сериализации таблицы стилей.

```csharp
public interface ICSSCharsetRule : ICSSRule
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../aspose.svg.dom.css/icsscharsetrule/encoding/) { get; set; } | Информация о кодировке, используемая в этом правиле @charset. |

### См. также

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
