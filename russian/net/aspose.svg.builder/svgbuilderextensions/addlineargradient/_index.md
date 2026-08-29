---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddLinearGradient. Добавляет конфигурацию элемента linearGradient в построитель."
type: docs
weight: 360
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

Добавляет конфигурацию элемента 'linearGradient' в конструктор.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'linearGradient'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

Добавляет элемент 'linearGradient' в SVG‑конструктор, указывая его начальные и конечные позиции, а также другие свойства градиента.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑построителя, к которому будет добавлен элемент 'linearGradient'. |
| x1 | Начальная координата x для градиента. Может быть типом double или ValueTuple с LengthType. |
| y1 | Начальная координата y для градиента. Может быть типом double или ValueTuple с LengthType. |
| x2 | Конечная координата x для градиента. Может быть типом double или ValueTuple с LengthType. |
| y2 | Конечная координата y для градиента. Может быть типом double или ValueTuple с LengthType. |
| gradientUnits | Указывает систему координат для градиента. Необязательный параметр. |
| spreadMethod | Определяет, как градиент распространяется за пределы своих начальной и конечной точек. Необязательный параметр. |
| href | Ссылка на другой градиент, если применимо. Необязательный параметр. |
| id | Уникальный идентификатор элемента градиента. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки построителя элемента линейного градиента. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
