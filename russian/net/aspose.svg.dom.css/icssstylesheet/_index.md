---
title: "ICSSStyleSheet Interface"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Css.ICSSStyleSheet interface. Интерфейс CSSStyleSheet является конкретным интерфейсом, используемым для представления таблицы стилей CSS, т.е. таблицы стилей с типом содержимого text/css."
type: docs
weight: 2660
url: /ru/net/aspose.svg.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

Интерфейс CSSStyleSheet — конкретный интерфейс, используемый для представления таблицы стилей CSS, т.е. таблицы стилей с типом содержимого "text/css".

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## Свойства

| Имя | Описание |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icssstylesheet/cssrules/) { get; } | Список всех правил CSS, содержащихся в таблице стилей. Он включает как наборы правил, так и at‑правила. |
| [OwnerRule](../../aspose.svg.dom.css/icssstylesheet/ownerrule/) { get; } | Если эта таблица стилей получена из правила @import, атрибут ownerRule будет содержать CSSImportRule. В этом случае атрибут ownerNode в интерфейсе StyleSheet будет равен null. Если таблица стилей получена из элемента или инструкции обработки, атрибут ownerRule будет равен null, а атрибут ownerNode будет содержать Node. |

## Методы

| Имя | Описание |
| --- | --- |
| [DeleteRule](../../aspose.svg.dom.css/icssstylesheet/deleterule/)(*int*) | Используется для удаления правила из таблицы стилей. |
| [InsertRule](../../aspose.svg.dom.css/icssstylesheet/insertrule/)(*string, int*) | Используется для вставки нового правила в таблицу стилей. Новое правило теперь становится частью каскада. |

### См. также

* interface [IStyleSheet](../istylesheet/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
