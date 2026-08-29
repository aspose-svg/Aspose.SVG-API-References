---
title: "Класс CSSValue"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Dom.Css.CSSValue. Представляет простое или сложное значение. Объект CSSValue встречается только в контексте свойства CSS."
type: docs
weight: 2490
url: /ru/net/aspose.svg.dom.css/cssvalue/
---
## CSSValue class

Представляет простое или сложное значение. Объект CSSValue встречается только в контексте свойства CSS.

```csharp
public abstract class CSSValue : DOMObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | Свойство CSSText интерфейса `CSSValue` представляет текущее вычисленное значение свойства CSS. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Код, определяющий тип значения. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Определяет, равен ли указанный объект этому экземпляру. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Возвращает хеш‑код для этого экземпляра. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | Этот метод используется для получения типа объекта ECMAScript. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Возвращает строку, представляющую этот экземпляр. |
| [operator ==](../../aspose.svg.dom.css/cssvalue/op_equality/) | Реализует оператор ==. |
| [operator !=](../../aspose.svg.dom.css/cssvalue/op_inequality/) | Реализует оператор !=. |

## Поля

| Имя | Описание |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.svg.dom.css/cssvalue/css_custom/) | Значение является пользовательским. |
| const [CSS_INHERIT](../../aspose.svg.dom.css/cssvalue/css_inherit/) | Значение наследуется, и cssText содержит "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../aspose.svg.dom.css/cssvalue/css_primitive_value/) | Значение является примитивным, и экземпляр интерфейса CSSPrimitiveValue можно получить, используя специфичные для привязки методы приведения типов к этому экземпляру интерфейса CSSValue. |
| const [CSS_VALUE_LIST](../../aspose.svg.dom.css/cssvalue/css_value_list/) | Значение представляет собой список CSSValue, и экземпляр интерфейса CSSValueList можно получить, используя специфичные для привязки методы приведения типов к этому экземпляру интерфейса CSSValue. |

### См. также

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
