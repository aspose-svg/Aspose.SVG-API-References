---
title: "SVGPoint Класс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.DataTypes.SVGPoint класс. Многие интерфейсы SVG DOM ссылаются на объекты класса SVGPoint. SVGPoint представляет собой пару координат x y. При использовании в матричных операциях SVGPoint рассматривается как вектор формы x y 1. Если объект SVGRect помечен как только для чтения, попытка изменить один из его атрибутов приведёт к выбросу исключения."
type: docs
weight: 2260
url: /ru/net/aspose.svg.datatypes/svgpoint/
---
## SVGPoint class

Многие интерфейсы SVG DOM ссылаются на объекты класса SVGPoint. SVGPoint представляет собой пару координат (x, y). При использовании в матричных операциях SVGPoint рассматривается как вектор вида: [x] [y] [1]. Если объект SVGRect помечен как только для чтения, попытка присвоить значение одному из его атрибутов приведёт к выбросу исключения.

```csharp
public class SVGPoint : SVGValueType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [X](../../aspose.svg.datatypes/svgpoint/x/) { get; set; } | Координата X. |
| [Y](../../aspose.svg.datatypes/svgpoint/y/) { get; set; } | Координата Y. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при необходимости — управляемые ресурсы. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [MatrixTransform](../../aspose.svg.datatypes/svgpoint/matrixtransform/)(*[SVGMatrix](../svgmatrix/)*) | Применяет 2x3 матричное преобразование к этому объекту SVGPoint и возвращает новый, преобразованный объект SVGPoint: newpoint = matrix* thispoint |
| override [ToString](../../aspose.svg.datatypes/svgpoint/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

### См. также

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
