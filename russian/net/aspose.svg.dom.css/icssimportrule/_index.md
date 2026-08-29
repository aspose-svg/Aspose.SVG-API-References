---
title: "Интерфейс ICSSImportRule"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Dom.Css.ICSSImportRule. Интерфейс CSSImportRule представляет правило импорта в таблице стилей CSS. Правило импорта используется для импорта правил стилей из других таблиц стилей"
type: docs
weight: 2560
url: /ru/net/aspose.svg.dom.css/icssimportrule/
---
## ICSSImportRule interface

Интерфейс CSSImportRule представляет правило @import в таблице стилей CSS. Правило @import используется для импорта правил стилей из других таблиц стилей.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Href](../../aspose.svg.dom.css/icssimportrule/href/) { get; } | Расположение таблицы стилей, которую нужно импортировать. Атрибут не будет содержать спецификатор "url(...)" вокруг URI. |
| [Media](../../aspose.svg.dom.css/icssimportrule/media/) { get; } | Список типов носителей, для которых может использоваться эта таблица стилей. |
| [StyleSheet](../../aspose.svg.dom.css/icssimportrule/stylesheet/) { get; } | Таблица стилей, на которую ссылается это правило, если она была загружена. Значение этого атрибута равно null, если таблица стилей ещё не загружена или не будет загружена (например, если таблица стилей предназначена для типа носителя, не поддерживаемого пользовательским агентом). |

### См. также

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
