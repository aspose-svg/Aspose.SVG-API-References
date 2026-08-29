---
title: "SVGBuilderExtensions.AddUse"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddUse. Добавляет конфигурацию элемента use в построитель"
type: docs
weight: 550
url: /ru/net/aspose.svg.builder/svgbuilderextensions/adduse/
---
## AddUse<TBuilder>(*this TBuilder, Action&lt;SVGUseElementBuilder&gt;*) {#adduse}

Добавляет конфигурацию элемента 'use' в построитель.

```csharp
public static TBuilder AddUse<TBuilder>(this TBuilder builder, 
    Action<SVGUseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'use'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGUseElementBuilder](../../svguseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddUse<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGUseElementBuilder&gt;*) {#adduse_1}

Добавляет элемент 'use' в SVG‑построитель, позволяя повторно использовать существующий элемент, определённый в другом месте SVG.

```csharp
public static TBuilder AddUse<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGUseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑builder, к которому будет добавлен элемент 'use'. |
| href | Ссылка на существующий элемент, который будет переиспользован. Необязательный параметр. |
| x | Координата x, где размещается переиспользуемый элемент. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| y | Координата y, где размещается переиспользуемый элемент. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| width | Ширина переиспользуемого элемента. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| height | Высота переиспользуемого элемента. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| fill | Цвет заливки, краска или идентификатор сервера заливки для элемента. Необязательный параметр. |
| stroke | Цвет обводки, краска или идентификатор сервера обводки для элемента. Необязательный параметр. |
| id | Уникальный идентификатор элемента. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки SVGUseElementBuilder. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGUseElementBuilder](../../svguseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
