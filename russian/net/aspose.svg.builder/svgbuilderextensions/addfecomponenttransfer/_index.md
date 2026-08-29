---
title: "SVGBuilderExtensions.AddFeComponentTransfer"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddFeComponentTransfer. Добавляет конфигурацию элемента feComponentTransfer в построитель. Этот элемент выполняет покомпонентное переназначение данных для цветовых каналов"
type: docs
weight: 150
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addfecomponenttransfer/
---
## AddFeComponentTransfer<TBuilder>(*this TBuilder, Action&lt;SVGFEComponentTransferElementBuilder&gt;*) {#addfecomponenttransfer}

Добавляет конфигурацию элемента 'feComponentTransfer' в построитель. Этот элемент выполняет по‑компонентное переназначение данных для цветовых каналов.

```csharp
public static TBuilder AddFeComponentTransfer<TBuilder>(this TBuilder builder, 
    Action<SVGFEComponentTransferElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'feComponentTransfer'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGFEComponentTransferElementBuilder](../../svgfecomponenttransferelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeComponentTransfer<TBuilder>(*this TBuilder, Action&lt;SVGFEFuncAElementBuilder&gt;, Action&lt;SVGFEFuncRElementBuilder&gt;, Action&lt;SVGFEFuncGElementBuilder&gt;, Action&lt;SVGFEFuncBElementBuilder&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEComponentTransferElementBuilder&gt;*) {#addfecomponenttransfer_1}

Добавляет элемент 'feComponentTransfer' в построитель SVG, позволяя выполнять по‑компонентное переназначение данных для цветовых каналов.

```csharp
public static TBuilder AddFeComponentTransfer<TBuilder>(this TBuilder builder, 
    Action<SVGFEFuncAElementBuilder> a = null, Action<SVGFEFuncRElementBuilder> r = null, 
    Action<SVGFEFuncGElementBuilder> g = null, Action<SVGFEFuncBElementBuilder> b = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEComponentTransferElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑строителя, к которому будет добавлен элемент 'feComponentTransfer'. |
| a | Действие для настройки компонента 'feFuncA' альфа‑канала. Необязательный параметр. |
| r | Действие для настройки компонента 'feFuncR' красного канала. Необязательный параметр. |
| g | Действие для настройки компонента 'feFuncG' зелёного канала. Необязательный параметр. |
| b | Действие для настройки компонента 'feFuncB' синего канала. Необязательный параметр. |
| in | Входные данные для эффекта переноса компонентов. Может быть строкой или объектом FilterInput. Необязательный параметр. |
| result | Идентификатор результата для этой примитивной фильтрации. Необязательный параметр. |
| x | Координата x подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| y | Координата y подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| width | Ширина подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| height | Высота подрегиона примитива фильтра. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| fill | Цвет заливки, краска или идентификатор сервера заливки для элемента. Необязательный параметр. |
| stroke | Цвет обводки, краска или идентификатор сервера обводки для элемента. Необязательный параметр. |
| id | Уникальный идентификатор элемента примитива фильтра. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки SVGFEComponentTransferElementBuilder. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* class [SVGFEFuncAElementBuilder](../../svgfefuncaelementbuilder/)
* class [SVGFEFuncRElementBuilder](../../svgfefuncrelementbuilder/)
* class [SVGFEFuncGElementBuilder](../../svgfefuncgelementbuilder/)
* class [SVGFEFuncBElementBuilder](../../svgfefuncbelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEComponentTransferElementBuilder](../../svgfecomponenttransferelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
