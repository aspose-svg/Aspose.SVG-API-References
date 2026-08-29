---
title: "ICSSStyleDeclaration интерфейс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Css.ICSSStyleDeclaration интерфейс. Интерфейс CSSStyleDeclaration представляет отдельный блок CSS‑объявлений. Этот интерфейс может использоваться для определения текущих свойств стиля в блоке или для явного задания свойств стиля внутри блока."
type: docs
weight: 2640
url: /ru/net/aspose.svg.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

Интерфейс CSSStyleDeclaration представляет отдельный блок объявлений CSS. Этот интерфейс может использоваться для определения текущих свойств стиля, установленных в блоке, или для явного задания свойств стиля внутри блока.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssstyledeclaration/csstext/) { get; set; } | Текстовое представление декларативного блока, пригодное для разбора (за исключением окружающих фигурных скобок). Установка этого атрибута приведёт к разбору нового значения и сбросу всех свойств в декларативном блоке, включая удаление или добавление свойств. |
| [Item](../../aspose.svg.dom.css/icssstyledeclaration/item/) { get; } | Используется для получения свойств, которые были явно заданы в этом декларативном блоке. Порядок получаемых свойств с помощью этого метода не обязателен совпадать с порядком их установки. Этот метод можно использовать для перебора всех свойств в этом декларативном блоке. |
| [Length](../../aspose.svg.dom.css/icssstyledeclaration/length/) { get; } | Количество свойств, которые были явно заданы в этом декларативном блоке. Диапазон допустимых индексов — от 0 до length-1 включительно. |
| [ParentRule](../../aspose.svg.dom.css/icssstyledeclaration/parentrule/) { get; } | CSS‑правило, которое содержит этот декларативный блок, или null, если этот CSSStyleDeclaration не привязан к CSSRule. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertycssvalue/)(*string*) | Используется для получения объектного представления значения CSS‑свойства, если оно было явно задано в этом декларативном блоке. Этот метод возвращает null, если свойство является сокращённым (shorthand). Значения сокращённых свойств могут быть доступны и изменяться только как строки с помощью методов getPropertyValue и setProperty. |
| [GetPropertyPriority](../../aspose.svg.dom.css/icssstyledeclaration/getpropertypriority/)(*string*) | Используется для получения приоритета CSS‑свойства (например, квалификатора "important") если свойство было явно задано в этом декларативном блоке. |
| [GetPropertyValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertyvalue/)(*string*) | Используется для получения значения CSS‑свойства, если оно было явно задано в этом декларативном блоке. |
| [RemoveProperty](../../aspose.svg.dom.css/icssstyledeclaration/removeproperty/)(*string*) | Используется для удаления CSS‑свойства, если оно было явно задано в этом декларативном блоке. |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty)(*string, string*) | Используется для установки значения свойства с приоритетом по умолчанию в этом декларативном блоке. Приоритет по умолчанию не является "important", т.е. String.Empty. |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(*string, string, string*) | Используется для установки значения свойства и приоритета в этом декларативном блоке. |

### См. также

* interface [ICSS2Properties](../icss2properties/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
