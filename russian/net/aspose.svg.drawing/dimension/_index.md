---
title: "Класс Dimension"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Drawing.Dimension. Предоставляет базовый класс для измерений. Общий термин «dimension» относится к числу с прикреплённой единицей измерения и обозначается типом UnitType"
type: docs
weight: 3410
url: /ru/net/aspose.svg.drawing/dimension/
---
## Dimension class

Предоставляет базовый класс для измерений. Общий термин «dimension» относится к числу с прикреплённой единицей измерения и обозначается [`UnitType`](../unittype/).

```csharp
public abstract class Dimension : Numeric
```

## Свойства

| Имя | Описание |
| --- | --- |
| [UnitType](../../aspose.svg.drawing/unit/unittype/) { get; } | Получает тип единицы измерения [`Unit`](../unit/). |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../aspose.svg.drawing/numeric/compareto/)(*[Numeric](../numeric/)*) | Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует за ним или находится в той же позиции в порядке сортировки, что и другой объект. |
| override [Equals](../../aspose.svg.drawing/unit/equals/)(*object*) | Определяет, равен ли указанный объект текущему экземпляру. |
| override [Equals](../../aspose.svg.drawing/numeric/equals/)(*[Unit](../unit/)*) | Определяет, равна ли указанная [`Unit`](../unit/) этому экземпляру. |
| override [GetHashCode](../../aspose.svg.drawing/numeric/gethashcode/)() | Возвращает хеш‑код для этого экземпляра. |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)() | Получает значение единицы. |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)(*[UnitType](../unittype/)*) | Получает значение, преобразованное к указанному [`UnitType`](../unittype/). |
| override [ToString](../../aspose.svg.drawing/dimension/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

### См. также

* class [Unit](../unit/)
* class [Numeric](../numeric/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
