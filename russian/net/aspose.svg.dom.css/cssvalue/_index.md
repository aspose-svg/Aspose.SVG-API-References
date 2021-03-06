---
title: CSSValue
second_title: Справочник по Aspose.SVG для .NET API
description: Представляет простое или сложное значение. Объект CSSValue встречается только в контексте свойства CSS.
type: docs
weight: 500
url: /ru/net/aspose.svg.dom.css/cssvalue/
---
## CSSValue class

Представляет простое или сложное значение. Объект CSSValue встречается только в контексте свойства CSS.

```csharp
public abstract class CSSValue : DOMObject
```

## Характеристики

| Имя | Описание |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext) { get; set; } | Строковое представление текущего значения. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype) { get; } | Код, определяющий тип значения. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals)(object) | Определяет, равен ли указанныйObjectэтому экземпляру. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode)() | Возвращает хэш-код для данного экземпляра. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype)() | Этот метод используется для получения объекта ECMAScriptType. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring)() | ВозвращаетString, представляющий этот экземпляр. |
| [operator ==](../../aspose.svg.dom.css/cssvalue/op_equality) | Реализует оператор ==. |
| [operator !=](../../aspose.svg.dom.css/cssvalue/op_inequality) | Реализует оператор !=. |

## Поля

| Имя | Описание |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.svg.dom.css/cssvalue/css_custom) | Значение является пользовательским. |
| const [CSS_INHERIT](../../aspose.svg.dom.css/cssvalue/css_inherit) | Значение наследуется, а cssText содержит "наследовать". |
| const [CSS_PRIMITIVE_VALUE](../../aspose.svg.dom.css/cssvalue/css_primitive_value) | Значение является примитивным значением, и экземпляр интерфейса CSSPrimitiveValue можно получить с помощью методов приведения типов для данного экземпляра интерфейса CSSValue. |
| const [CSS_VALUE_LIST](../../aspose.svg.dom.css/cssvalue/css_value_list) | Значение представляет собой список CSSValue, и экземпляр интерфейса CSSValueList можно получить, используя методы приведения типов для данного экземпляра интерфейса CSSValue. |

### Смотрите также

* class [DOMObject](../../aspose.svg.dom/domobject)
* пространство имен [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css)
* сборка [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
