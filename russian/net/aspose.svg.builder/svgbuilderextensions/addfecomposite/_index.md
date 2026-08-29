---
title: "SVGBuilderExtensions.AddFeComposite"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddFeComposite. Добавляет конфигурацию элемента feComposite в построитель. Этот элемент выполняет побитовое комбинирование двух входных графических объектов."
type: docs
weight: 160
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addfecomposite/
---
## AddFeComposite<TBuilder>(*this TBuilder, Action&lt;SVGFECompositeElementBuilder&gt;*) {#addfecomposite}

Добавляет конфигурацию элемента 'feComposite' в построитель. Этот элемент выполняет побитовую комбинацию двух входных графических объектов.

```csharp
public static TBuilder AddFeComposite<TBuilder>(this TBuilder builder, 
    Action<SVGFECompositeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'feComposite'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGFECompositeElementBuilder](../../svgfecompositeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeComposite<TBuilder>(*this TBuilder, CompositeOperator?, double?, double?, double?, double?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFECompositeElementBuilder&gt;*) {#addfecomposite_1}

Добавляет элемент 'feComposite' в конструктор SVG, указывая операцию композитинга и различные свойства для комбинирования входных изображений.

```csharp
public static TBuilder AddFeComposite<TBuilder>(this TBuilder builder, 
    CompositeOperator? compositeOperator, double? k1, double? k2, double? k3, double? k4, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFECompositeElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑builder, к которому будет добавлен элемент 'feComposite'. |
| compositeOperator | Оператор композитинга, который будет использоваться. Необязательный параметр. |
| k1 | Первое числовое значение для операции композитинга. Необязательный параметр. |
| k2 | Второе числовое значение для операции композитинга. Необязательный параметр. |
| k3 | Третье числовое значение для операции композитинга. Необязательный параметр. |
| k4 | Четвёртое числовое значение для операции композитинга. Необязательный параметр. |
| in | Первый вход для эффекта композитинга. Может быть строкой или объектом FilterInput. Необязательный параметр. |
| in2 | Второй вход для эффекта композитинга. Может быть строкой или объектом FilterInput. Необязательный параметр. |
| result | Идентификатор результата для этой примитивной фильтрации. Необязательный параметр. |
| x | Координата x подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| y | Координата y подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| width | Ширина подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| height | Высота подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| fill | Цвет заливки, краска или идентификатор сервера заливки для элемента. Необязательный параметр. |
| stroke | Цвет обводки, краска или идентификатор сервера обводки для элемента. Необязательный параметр. |
| id | Уникальный идентификатор элемента примитива фильтра. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки SVGFECompositeElementBuilder. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* enum [CompositeOperator](../../compositeoperator/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFECompositeElementBuilder](../../svgfecompositeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
