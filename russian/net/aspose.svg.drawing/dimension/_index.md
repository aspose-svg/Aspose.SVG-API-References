---
title: Dimension
second_title: Справочник по Aspose.SVG для .NET API
description: Предоставляет базовый класс для измерений. Общий термин размер относится к числу с прикрепленной к нему единицей измерения и обозначается какUnitType./unittype.
type: docs
weight: 1400
url: /ru/net/aspose.svg.drawing/dimension/
---
## Dimension class

Предоставляет базовый класс для измерений. Общий термин «размер» относится к числу с прикрепленной к нему единицей измерения и обозначается как[`UnitType`](../unittype).

```csharp
public abstract class Dimension : Numeric
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [UnitType](../../aspose.svg.drawing/unit/unittype) { get; } | Получает тип единицы измерения[`Unit`](../unit). |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../aspose.svg.drawing/numeric/compareto)(Numeric) | Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует за ним или находится в той же позиции в порядке сортировки, что и другой объект . |
| override [Equals](../../aspose.svg.drawing/unit/equals)(object) | Определяет, равен ли указанныйObjectэтому экземпляру. |
| override [Equals](../../aspose.svg.drawing/numeric/equals)(Unit) | Определяет, равен ли указанный[`Unit`](../unit)этому экземпляру. |
| override [GetHashCode](../../aspose.svg.drawing/numeric/gethashcode)() | Возвращает хэш-код для данного экземпляра. |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue)() | Получает значение единицы измерения. |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue)(UnitType) | Получает значение, преобразованное в указанный[`UnitType`](../unittype). |
| override [ToString](../../aspose.svg.drawing/dimension/tostring)() | ВозвращаетString, представляющий этот экземпляр. |

### Смотрите также

* class [Unit](../unit)
* class [Numeric](../numeric)
* пространство имен [Aspose.Svg.Drawing](../../aspose.svg.drawing)
* сборка [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->