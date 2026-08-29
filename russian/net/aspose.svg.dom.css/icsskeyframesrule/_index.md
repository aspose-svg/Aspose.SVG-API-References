---
title: "Интерфейс ICSSKeyframesRule"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Css.ICSSKeyframesRule интерфейс. Интерфейс CSSKeyframesRule представляет полный набор ключевых кадров для одной анимации."
type: docs
weight: 2580
url: /ru/net/aspose.svg.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

Интерфейс CSSKeyframesRule представляет полный набор ключевых кадров для одной анимации.

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## Свойства

| Имя | Описание |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icsskeyframesrule/cssrules/) { get; } | Этот атрибут предоставляет доступ к ключевым кадрам в списке. |
| [Name](../../aspose.svg.dom.css/icsskeyframesrule/name/) { get; } | Этот атрибут является именем ключевых кадров, используемым свойством ‘animation-name’. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendRule](../../aspose.svg.dom.css/icsskeyframesrule/appendrule/)(*string*) | Метод appendRule добавляет переданный CSSKeyframeRule в список по переданному ключу. |
| [DeleteRule](../../aspose.svg.dom.css/icsskeyframesrule/deleterule/)(*string*) | Метод deleteRule удаляет CSSKeyframeRule с переданным ключом. Если правило с этим ключом не существует, метод ничего не делает. |
| [FindRule](../../aspose.svg.dom.css/icsskeyframesrule/findrule/)(*string*) | Метод findRule возвращает правило с ключом, совпадающим с переданным ключом. Если такого правила нет, возвращается значение null. |

### См. также

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
