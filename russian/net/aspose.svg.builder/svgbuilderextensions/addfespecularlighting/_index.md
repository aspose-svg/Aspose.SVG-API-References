---
title: "SVGBuilderExtensions.AddFeSpecularLighting"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddFeSpecularLighting. Добавляет конфигурацию элемента feSpecularLighting в построитель. Этот элемент применяет световой эффект к изображению, имитируя зеркальное отражение."
type: docs
weight: 270
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addfespecularlighting/
---
## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_2}

Добавляет конфигурацию элемента 'feSpecularLighting' в конструктор. Этот элемент применяет эффект освещения к изображению, имитируя зеркальное отражение.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpecularLightingElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие настройки для элемента 'feSpecularLighting'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDistantLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting}

Добавляет элемент 'feSpecularLighting' в конструктор SVG, применяя эффект зеркального освещения с использованием указанного источника света.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDistantLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑builder, к которому будет добавлен элемент 'feSpecularLighting'. |
| lightSource | Действие для настройки источника света для эффекта зеркального освещения. |
| lightingColor | Цвет света. Необязательный параметр. |
| surfaceScale | Коэффициент масштабирования поверхности для светового эффекта. Необязательный параметр. |
| specularConstant | Константа, используемая для масштабирования зеркального компонента. Необязательный параметр. |
| specularExponent | Экспонента для зеркального компонента, контролирующая фокусировку зеркального блика. Необязательный параметр. |
| kernelUnitLength | Длина единицы ядра для свёрточного фильтра. Может быть типом double или ValueTuple из двух double. Необязательный параметр. |
| in | Входное изображение, к которому будет применён эффект зеркального освещения. Может быть строкой или FilterInput. Необязательный параметр. |
| result | Идентификатор результата для этой примитивной фильтрации. Необязательный параметр. |
| x | Координата x подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| y | Координата y подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| width | Ширина подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| height | Высота подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| fill | Цвет заливки, краска или идентификатор сервера заливки для элемента. Необязательный параметр. |
| stroke | Цвет обводки, краска или идентификатор сервера обводки для элемента. Необязательный параметр. |
| id | Уникальный идентификатор элемента примитива фильтра. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки SVGFESpecularLightingElementBuilder. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* class [SVGFEDistantLightElementBuilder](../../svgfedistantlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEPointLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_1}

Добавляет элемент 'feSpecularLighting' в конструктор SVG, применяя эффект зеркального освещения с использованием указанного источника света.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEPointLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑builder, к которому будет добавлен элемент 'feSpecularLighting'. |
| lightSource | Действие для настройки источника света для эффекта зеркального освещения. |
| lightingColor | Цвет света. Необязательный параметр. |
| surfaceScale | Коэффициент масштабирования поверхности для светового эффекта. Необязательный параметр. |
| specularConstant | Константа, используемая для масштабирования зеркального компонента. Необязательный параметр. |
| specularExponent | Экспонента для зеркального компонента, контролирующая фокусировку зеркального блика. Необязательный параметр. |
| kernelUnitLength | Длина единицы ядра для свёрточного фильтра. Может быть типом double или ValueTuple из двух double. Необязательный параметр. |
| in | Входное изображение, к которому будет применён эффект зеркального освещения. Может быть строкой или FilterInput. Необязательный параметр. |
| result | Идентификатор результата для этой примитивной фильтрации. Необязательный параметр. |
| x | Координата x подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| y | Координата y подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| width | Ширина подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| height | Высота подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| fill | Цвет заливки, краска или идентификатор сервера заливки для элемента. Необязательный параметр. |
| stroke | Цвет обводки, краска или идентификатор сервера обводки для элемента. Необязательный параметр. |
| id | Уникальный идентификатор элемента примитива фильтра. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки SVGFESpecularLightingElementBuilder. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* class [SVGFEPointLightElementBuilder](../../svgfepointlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpotLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_3}

Добавляет элемент 'feSpecularLighting' в конструктор SVG, применяя эффект зеркального освещения с использованием указанного источника света.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpotLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑builder, к которому будет добавлен элемент 'feSpecularLighting'. |
| lightSource | Действие для настройки источника света для эффекта зеркального освещения. |
| lightingColor | Цвет света. Необязательный параметр. |
| surfaceScale | Коэффициент масштабирования поверхности для светового эффекта. Необязательный параметр. |
| specularConstant | Константа, используемая для масштабирования зеркального компонента. Необязательный параметр. |
| specularExponent | Экспонента для зеркального компонента, контролирующая фокусировку зеркального блика. Необязательный параметр. |
| kernelUnitLength | Длина единицы ядра для свёрточного фильтра. Может быть типом double или ValueTuple из двух double. Необязательный параметр. |
| in | Входное изображение, к которому будет применён эффект зеркального освещения. Может быть строкой или FilterInput. Необязательный параметр. |
| result | Идентификатор результата для этой примитивной фильтрации. Необязательный параметр. |
| x | Координата x подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| y | Координата y подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| width | Ширина подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| height | Высота подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| fill | Цвет заливки, краска или идентификатор сервера заливки для элемента. Необязательный параметр. |
| stroke | Цвет обводки, краска или идентификатор сервера обводки для элемента. Необязательный параметр. |
| id | Уникальный идентификатор элемента примитива фильтра. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки SVGFESpecularLightingElementBuilder. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* class [SVGFESpotLightElementBuilder](../../svgfespotlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
