---
title: SVGAnimatedValueT
second_title: Справочник по Aspose.SVG для .NET API
description: Используется для атрибутов типов которые можно анимировать.
type: docs
weight: 220
url: /ru/net/aspose.svg.datatypes/svganimatedvalue-1/
---
## SVGAnimatedValue&lt;T&gt; class

Используется для атрибутов типов, которые можно анимировать.

```csharp
public abstract class SVGAnimatedValue<T> : SVGValueType
```

| Параметр | Описание |
| --- | --- |
| T | Объект SVG Value. |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [AnimVal](../../aspose.svg.datatypes/svganimatedvalue`1/animval) { get; } | Если данный атрибут или свойство анимируются, содержит текущее анимированное значение атрибута или свойства. Если данный атрибут или свойство в настоящее время не анимируются, содержит то же значение, что и baseVal. |
| [BaseVal](../../aspose.svg.datatypes/svganimatedvalue`1/baseval) { get; set; } | Базовое значение данного атрибута до применения любых анимаций. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose)() | Освобождает неуправляемые и (необязательно) управляемые ресурсы. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Этот метод используется для получения объекта ECMAScriptType. |

### Смотрите также

* class [SVGValueType](../svgvaluetype)
* пространство имен [Aspose.Svg.DataTypes](../../aspose.svg.datatypes)
* сборка [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->