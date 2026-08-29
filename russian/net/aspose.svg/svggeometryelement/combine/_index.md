---
title: "SVGGeometryElement.Combine"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Combine SVGGeometryElement. Объединяет эту геометрию с другой SVG‑геометрией с помощью булевой операции и возвращает новый элемент пути, содержащий результат."
type: docs
weight: 20
url: /ru/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

Объединяет эту геометрию с другой SVG-геометрией с помощью булевой операции и возвращает новый элемент `<path>`, содержащий результат.

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | Другая геометрия, с которой нужно объединить. Должна находиться в том же документе. |
| op | BooleanPathOp | Булевый оператор для применения: Union (A UNION B), Difference (A - B), Intersection (A INTERSECT B) или Exclusion (XOR). |

### Возвращаемое значение

Новый [`SVGPathElement`](../../svgpathelement/), чей атрибут `d` кодирует результат в пользовательском пространстве корневого `<svg>` (CSS px). Элемент не добавляется в DOM.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, если *geometryElement* равно null. |
| InvalidOperationException | Выбрасывается, если у этого элемента нет родительского документа. |
| NotSupportedException | Выбрасывается, когда булевые операции с путями недоступны; эта функция требует бэкенда SkiaSharp (установите пакет Aspose.SVG.Drawing.SkiaSharp). |

### См. также

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
