---
title: "Класс SVGAnimatedValueT"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.DataTypes.SVGAnimatedValue1T. Используется для атрибутов типов, которые могут быть анимированы"
type: docs
weight: 2200
url: /ru/net/aspose.svg.datatypes/svganimatedvalue-1/
---
## SVGAnimatedValue<T> class

Используется для атрибутов типов, которые могут быть анимированы.

```csharp
public abstract class SVGAnimatedValue<T> : SVGValueType
```

| Параметр | Описание |
| --- | --- |
| T | Объект SVG Value. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [AnimVal](../../aspose.svg.datatypes/svganimatedvalue-1/animval/) { get; } | Если указанный атрибут или свойство анимируется, содержит текущее анимированное значение атрибута или свойства. Если указанный атрибут или свойство в данный момент не анимируется, содержит то же значение, что и baseVal. |
| [BaseVal](../../aspose.svg.datatypes/svganimatedvalue-1/baseval/) { get; set; } | Базовое значение указанного атрибута до применения любых анимаций. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при необходимости — управляемые ресурсы. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |

### См. также

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
