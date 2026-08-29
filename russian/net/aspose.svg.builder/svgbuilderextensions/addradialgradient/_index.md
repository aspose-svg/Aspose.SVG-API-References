---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddRadialGradient. Добавляет конфигурацию элемента radialGradient в билдер"
type: docs
weight: 440
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

Добавляет конфигурацию элемента 'radialGradient' в конструктор.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'radialGradient'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

Добавляет элемент 'radialGradient' в SVG‑конструктор, указывая его центр, радиус и фокусные точки, а также другие свойства градиента.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑билдера, к которому будет добавлен элемент 'radialGradient'. |
| cx | Координата x центра градиента. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| cy | Координата y центра градиента. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| r | Радиус градиента. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| fx | Координата x фокусной точки градиента. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| fy | Y‑координата фокусной точки градиента. Может быть типа double или ValueTuple с LengthType. Необязательный параметр. |
| gradientUnits | Указывает систему координат для градиента. Необязательный параметр. |
| spreadMethod | Определяет, как градиент распространяется за пределы своих начальной и конечной точек. Необязательный параметр. |
| href | Ссылка на другой градиент, если применимо. Необязательный параметр. |
| id | Уникальный идентификатор элемента градиента. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки построителя радиального градиентного элемента. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
