---
title: "CSSValueList Class"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Css.CSSValueList class. Интерфейс CSSValueList предоставляет абстракцию упорядоченной коллекции значений CSS."
type: docs
weight: 2500
url: /ru/net/aspose.svg.dom.css/cssvaluelist/
---
## CSSValueList class

Интерфейс CSSValueList предоставляет абстракцию упорядоченной коллекции значений CSS.

```csharp
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | Инициализирует новый экземпляр класса `CSSValueList`. |
| [CSSValueList](cssvaluelist/#constructor_1)(*params CSSValue[]*) | Инициализирует новый экземпляр класса `CSSValueList`. |
| [CSSValueList](cssvaluelist/#constructor_2)(*IEnumerable&lt;CSSValue&gt;*) | Инициализирует новый экземпляр класса `CSSValueList`. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [CSSText](../../aspose.svg.dom.css/cssvaluelist/csstext/) { get; set; } | Свойство CSSText интерфейса [`CSSValue`](../cssvalue/) представляет текущее вычисленное значение свойства CSS. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Код, определяющий тип значения. |
| [Item](../../aspose.svg.dom.css/cssvaluelist/item/) { get; } | Возвращает [`CSSValue`](../cssvalue/) по указанному индексу. |
| [Length](../../aspose.svg.dom.css/cssvaluelist/length/) { get; } | Свойство length только для чтения интерфейса CSSValueList представляет количество CSSValue в списке. Диапазон допустимых значений индексов — от 0 до length‑1 включительно. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Определяет, равен ли указанный объект этому экземпляру. |
| [GetEnumerator](../../aspose.svg.dom.css/cssvaluelist/getenumerator/)() | Возвращает перечислитель, который проходит по коллекции. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Возвращает хеш‑код для этого экземпляра. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvaluelist/getplatformtype/)() | Этот метод используется для получения типа объекта ECMAScript. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

### См. также

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
