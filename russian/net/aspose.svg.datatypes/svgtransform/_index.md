---
title: "Класс SVGTransform"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.DataTypes.SVGTransform. SVGTransform — это интерфейс одной из компонентных трансформаций внутри SVGTransformList, поэтому объект SVGTransform соответствует отдельному компоненту, например масштабированию или матрице, в спецификации атрибута transform."
type: docs
weight: 2310
url: /ru/net/aspose.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform — это интерфейс одной из компонентных трансформаций внутри SVGTransformList; таким образом, объект SVGTransform соответствует отдельной компоненте (например, 'scale(…)' или 'matrix(…)') в спецификации атрибута ‘transform’.

```csharp
public class SVGTransform : SVGValueType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Angle](../../aspose.svg.datatypes/svgtransform/angle/) { get; } | Удобный атрибут для SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX и SVG_TRANSFORM_SKEWY. Он хранит указанное значение угла. Для SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE и SVG_TRANSFORM_SCALE угол будет равен нулю. |
| [Matrix](../../aspose.svg.datatypes/svgtransform/matrix/) { get; } | Матрица, представляющая эту трансформацию. Объект матрицы является живым, что означает, что любые изменения, внесённые в объект SVGTransform, немедленно отражаются в объекте матрицы и наоборот. Если объект матрицы изменяется напрямую (т.е. без использования методов интерфейса SVGTransform), тип SVGTransform меняется на SVG_TRANSFORM_MATRIX. Для SVG_TRANSFORM_MATRIX матрица содержит значения a, b, c, d, e, f, предоставленные пользователем. Для SVG_TRANSFORM_TRANSLATE e и f представляют величины трансляции (a=1, b=0, c=0, d=1). Для SVG_TRANSFORM_SCALE a и d представляют коэффициенты масштабирования (b=0, c=0, e=0, f=0). Для SVG_TRANSFORM_SKEWX и SVG_TRANSFORM_SKEWY a, b, c и d представляют матрицу, которая даст указанное наклонение (e=0 и f=0). Для SVG_TRANSFORM_ROTATE a, b, c, d, e и f вместе представляют матрицу, которая даст указанное вращение. Когда вращение происходит вокруг центральной точки (0, 0), e и f будут равны нулю. |
| [Type](../../aspose.svg.datatypes/svgtransform/type/) { get; } | Тип значения, указанный одним из констант SVG_TRANSFORM_*, определённых в этом интерфейсе. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при необходимости — управляемые ресурсы. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [SetMatrix](../../aspose.svg.datatypes/svgtransform/setmatrix/)(*[SVGMatrix](../svgmatrix/)*) | Устанавливает тип трансформации в SVG_TRANSFORM_MATRIX, с параметром matrix, определяющим новую трансформацию. Значения из параметра matrix копируются, параметр matrix не заменяет SVGTransform::matrix. |
| [SetRotate](../../aspose.svg.datatypes/svgtransform/setrotate/)(*float, float, float*) | Устанавливает тип трансформации в SVG_TRANSFORM_ROTATE, с параметром angle, определяющим угол вращения, и параметрами cx и cy, определяющими необязательный центр вращения. |
| [SetScale](../../aspose.svg.datatypes/svgtransform/setscale/)(*float, float*) | Устанавливает тип трансформации в SVG_TRANSFORM_SCALE, с параметрами sx и sy, определяющими коэффициенты масштабирования. |
| [SetSkewX](../../aspose.svg.datatypes/svgtransform/setskewx/)(*float*) | Устанавливает тип трансформации в SVG_TRANSFORM_SKEWX, с параметром angle, определяющим величину наклона по оси X. |
| [SetSkewY](../../aspose.svg.datatypes/svgtransform/setskewy/)(*float*) | Устанавливает тип трансформации в SVG_TRANSFORM_SKEWY, с параметром angle, определяющим величину наклона по оси Y. |
| [SetTranslate](../../aspose.svg.datatypes/svgtransform/settranslate/)(*float, float*) | Устанавливает тип преобразования в SVG_TRANSFORM_TRANSLATE, с параметрами tx и ty, определяющими величины трансляции. |
| override [ToString](../../aspose.svg.datatypes/svgtransform/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.svg.datatypes/svgtransform/svg_transform_matrix/) | Трансформация 'matrix(…)'. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.svg.datatypes/svgtransform/svg_transform_rotate/) | Трансформация 'rotate(…)'. |
| const [SVG_TRANSFORM_SCALE](../../aspose.svg.datatypes/svgtransform/svg_transform_scale/) | Трансформация 'scale(…)'. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.svg.datatypes/svgtransform/svg_transform_skewx/) | Трансформация 'skewX(…)'. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.svg.datatypes/svgtransform/svg_transform_skewy/) | Трансформация 'skewY(…)'. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.svg.datatypes/svgtransform/svg_transform_translate/) | Трансформация 'translate(…)'. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.svg.datatypes/svgtransform/svg_transform_unknown/) | Тип единицы не является одним из предопределённых типов. Недопустимо пытаться определить новое значение этого типа или пытаться переключить существующее значение на этот тип. |

### См. также

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
