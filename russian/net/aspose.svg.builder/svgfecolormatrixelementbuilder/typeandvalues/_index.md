---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод TypeAndValues класса SVGFEColorMatrixElementBuilder. Устанавливает атрибуты type и values элемента feColorMatrix, задавая операцию цветовой матрицы и её параметры"
type: docs
weight: 30
url: /ru/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

Устанавливает атрибуты 'type' и 'values' элемента feColorMatrix, задавая операцию цветовой матрицы и её параметры.

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | ColorMatrixOperation | Значение перечисления ColorMatrixOperation, представляющее тип операции цветовой матрицы. |
| значения | Double[] | Параметры операции с цветовой матрицей. |

### Возвращаемое значение

Текущий экземпляр построителя.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда предоставленные значения не соответствуют требованиям указанного типа. |
| NotSupportedException | Выбрасывается, когда предоставлен неподдерживаемый тип операции с матрицей. |

### См. также

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
