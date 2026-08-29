---
title: "SVGBuilderExtensions.AddFilter"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddFilter. Добавляет конфигурацию элемента filter в конструктор."
type: docs
weight: 300
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

Добавляет конфигурацию элемента 'filter' в конструктор.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'filter'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

Добавляет элемент 'filter' в SVG‑конструктор, определяя эффект фильтра, который можно применить к элементам SVG.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑конструктора, к которому будет добавлен элемент 'filter'. |
| filterUnits | Указывает систему координат для атрибутов x, y, width и height фильтра. Необязательный параметр. |
| primitiveUnits | Указывает систему координат для атрибутов дочерних элементов фильтра. Необязательный параметр. |
| x | Координата x области фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| y | Координата y области фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| width | Ширина области фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| height | Высота области фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| fill | Цвет заливки или кисть для элемента фильтра. Необязательный параметр. |
| stroke | Цвет обводки или кисть для элемента фильтра. Необязательный параметр. |
| id | Уникальный идентификатор элемента фильтра. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки SVGFilterElementBuilder. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
