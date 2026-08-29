---
title: "Класс SVGMatrix"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.DataTypes.SVGMatrix. Многие графические операции SVG используют 2x3 матрицы вида a c e b d f, которые при расширении до 3x3 матрицы для целей арифметики матриц становятся a c e b d f 0 0 1."
type: docs
weight: 2230
url: /ru/net/aspose.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Многие графические операции SVG используют 2x3 матрицы вида: [a c e] [b d f], которые при расширении до 3x3 матрицы для целей матричной арифметики становятся: [a c e] [b d f] [0 0 1]

```csharp
public class SVGMatrix : SVGValueType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [A](../../aspose.svg.datatypes/svgmatrix/a/) { get; set; } | Компонент A матрицы. |
| [B](../../aspose.svg.datatypes/svgmatrix/b/) { get; set; } | Компонент B матрицы. |
| [C](../../aspose.svg.datatypes/svgmatrix/c/) { get; set; } | Компонент C матрицы. |
| [D](../../aspose.svg.datatypes/svgmatrix/d/) { get; set; } | Компонент D матрицы. |
| [E](../../aspose.svg.datatypes/svgmatrix/e/) { get; set; } | Компонент E матрицы. |
| [F](../../aspose.svg.datatypes/svgmatrix/f/) { get; set; } | Компонент F матрицы. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при необходимости — управляемые ресурсы. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [Multiply](../../aspose.svg.datatypes/svgmatrix/multiply/)(*SVGMatrix*) | Выполняет умножение матриц. Эта матрица умножается справа на другую матрицу, возвращая полученную новую матрицу. |
| [Rotate](../../aspose.svg.datatypes/svgmatrix/rotate/)(*float*) | Умножает текущую матрицу справа на преобразование вращения и возвращает полученную матрицу. |
| [Scale](../../aspose.svg.datatypes/svgmatrix/scale/)(*float*) | Умножает текущую матрицу справа на преобразование равномерного масштабирования и возвращает полученную матрицу. |
| [ScaleNonUniform](../../aspose.svg.datatypes/svgmatrix/scalenonuniform/)(*float, float*) | Применяет постмультипликацию преобразования неравномерного масштабирования к текущей матрице и возвращает полученную матрицу. |
| [SkewX](../../aspose.svg.datatypes/svgmatrix/skewx/)(*float*) | Применяет постмультипликацию преобразования skewX к текущей матрице и возвращает полученную матрицу. |
| [SkewY](../../aspose.svg.datatypes/svgmatrix/skewy/)(*float*) | Применяет постмультипликацию преобразования skewY к текущей матрице и возвращает полученную матрицу. |
| override [ToString](../../aspose.svg.datatypes/svgmatrix/tostring/)() | Возвращает строку, представляющую этот экземпляр. |
| [Translate](../../aspose.svg.datatypes/svgmatrix/translate/)(*float, float*) | Применяет постмультипликацию преобразования перемещения к текущей матрице и возвращает полученную матрицу. |

### См. также

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
