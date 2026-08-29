---
title: "SVGBuilderExtensions.AddFeTurbulence"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddFeTurbulence. Добавляет конфигурацию элемента feTurbulence в построитель. Этот элемент создает изображение с использованием шума Перлина, полезного для создания текстур, таких как облака или мрамор."
type: docs
weight: 290
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addfeturbulence/
---
## AddFeTurbulence<TBuilder>(*this TBuilder, Action&lt;SVGFETurbulenceElementBuilder&gt;*) {#addfeturbulence_1}

Добавляет конфигурацию элемента 'feTurbulence' в конструктор. Этот элемент создает изображение с использованием шума Перлина, полезного для создания текстур, таких как облака или мрамор.

```csharp
public static TBuilder AddFeTurbulence<TBuilder>(this TBuilder builder, 
    Action<SVGFETurbulenceElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'feTurbulence'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGFETurbulenceElementBuilder](../../svgfeturbulenceelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeTurbulence<TBuilder>(*this TBuilder, OneOf&lt;double, (double, double)&gt;, int?, double?, StitchTiles?, TurbulenceType?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFETurbulenceElementBuilder&gt;*) {#addfeturbulence}

Добавляет элемент 'feTurbulence' в SVG‑builder, создавая эффект турбулентности, например облака или мрамор, с использованием шума Перлина.

```csharp
public static TBuilder AddFeTurbulence<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, double)> baseFrequency = null, int? numOctaves = null, 
    double? seed = null, StitchTiles? stitchTiles = default, TurbulenceType? type = default, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFETurbulenceElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑builder, к которому будет добавлен элемент 'feTurbulence'. |
| baseFrequency | Базовая частота турбулентности. Может быть типом double или ValueTuple из двух double. Необязательный параметр. |
| numOctaves | Количество октав для турбулентности. Необязательный параметр. |
| seed | Значение seed для генератора случайных чисел. Необязательный параметр. |
| stitchTiles | Указывает, объединены ли плитки вместе. Необязательный параметр. |
| type | Тип турбулентности (фрактальный шум или турбулентность). Необязательный параметр. |
| in | Входное изображение, к которому будет применён эффект турбулентности. Может быть строкой или FilterInput. Необязательный параметр. |
| result | Идентификатор результата для этой примитивной фильтрации. Необязательный параметр. |
| x | Координата x подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| y | Координата y подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| width | Ширина подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| height | Высота подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| fill | Цвет заливки, краска или идентификатор сервера заливки для элемента. Необязательный параметр. |
| stroke | Цвет обводки, краска или идентификатор сервера обводки для элемента. Необязательный параметр. |
| id | Уникальный идентификатор элемента примитива фильтра. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки SVGFETurbulenceElementBuilder. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [StitchTiles](../../stitchtiles/)
* enum [TurbulenceType](../../turbulencetype/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFETurbulenceElementBuilder](../../svgfeturbulenceelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
