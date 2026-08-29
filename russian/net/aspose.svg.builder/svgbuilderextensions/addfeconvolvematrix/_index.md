---
title: "SVGBuilderExtensions.AddFeConvolveMatrix"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод AddFeConvolveMatrix класса SVGBuilderExtensions. Добавляет конфигурацию элемента feConvolveMatrix в построитель. Этот элемент применяет фильтр свёртки матрицы."
type: docs
weight: 170
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addfeconvolvematrix/
---
## AddFeConvolveMatrix<TBuilder>(*this TBuilder, Action&lt;SVGFEConvolveMatrixElementBuilder&gt;*) {#addfeconvolvematrix_1}

Добавляет конфигурацию элемента 'feConvolveMatrix' в конструктор. Этот элемент применяет эффект фильтра свертки матрицы.

```csharp
public static TBuilder AddFeConvolveMatrix<TBuilder>(this TBuilder builder, 
    Action<SVGFEConvolveMatrixElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'feConvolveMatrix'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGFEConvolveMatrixElementBuilder](../../svgfeconvolvematrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeConvolveMatrix<TBuilder>(*this TBuilder, double[], double?, double?, int?, int?, EdgeMode?, bool?, OneOf&lt;int, (int, int)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEConvolveMatrixElementBuilder&gt;*) {#addfeconvolvematrix}

Добавляет элемент 'feConvolveMatrix' в конструктор SVG, применяя эффект фильтра свертки матрицы.

```csharp
public static TBuilder AddFeConvolveMatrix<TBuilder>(this TBuilder builder, 
    double[] kernelMatrix = null, double? divisor = null, double? bias = null, int? targetX = null, 
    int? targetY = null, EdgeMode? edgeMode = default, bool? preserveAlpha = null, 
    OneOf<int, (int, int)> order = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEConvolveMatrixElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑builder, к которому будет добавлен элемент 'feConvolveMatrix'. |
| kernelMatrix | Матрица значений для свёртки. Необязательный параметр. |
| делитель | Делитель для свёртки. Необязательный параметр. |
| смещение | Смещение, добавляемое к результату свёртки. Необязательный параметр. |
| targetX | Координата X целевого пикселя в матрице ядра. Необязательный параметр. |
| targetY | Координата Y целевого пикселя в матрице ядра. Необязательный параметр. |
| edgeMode | Определяет, как обрабатывать граничные пиксели при свёртке. Необязательный параметр. |
| preserveAlpha | Указывает, сохранять ли альфа-канал. Необязательный параметр. |
| order | Порядок матрицы ядра. Может быть целым числом или кортежем из двух целых чисел. Необязательный параметр. |
| in | Входные данные для эффекта свёртки. Может быть строкой или объектом FilterInput. Необязательный параметр. |
| result | Идентификатор результата для этой примитивной фильтрации. Необязательный параметр. |
| x | Координата x подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| y | Координата y подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| width | Ширина подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| height | Высота подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| fill | Цвет заливки, краска или идентификатор сервера заливки для элемента. Необязательный параметр. |
| stroke | Цвет обводки, краска или идентификатор сервера обводки для элемента. Необязательный параметр. |
| id | Уникальный идентификатор элемента примитива фильтра. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки SVGFEConvolveMatrixElementBuilder. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* enum [EdgeMode](../../edgemode/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEConvolveMatrixElementBuilder](../../svgfeconvolvematrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
