---
title: "SVGBuilderExtensions.AddRect"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddRect. Добавляет конфигурацию элемента rect в построитель"
type: docs
weight: 450
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addrect/
---
## AddRect<TBuilder>(*this TBuilder, Action&lt;SVGRectElementBuilder&gt;*) {#addrect_1}

Добавляет конфигурацию элемента 'rect' в построитель.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    Action<SVGRectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'rect'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRect<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGRectElementBuilder&gt;*) {#addrect}

Добавляет элемент 'rect' (прямоугольник) с указанными размерами и стилями в SVG‑построитель.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGRectElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑построителя, к которому будет добавлен элемент 'rect'. |
| x | Координата x начальной точки прямоугольника. Может быть значением типа double или кортежем из double и LengthType. |
| y | Координата y начальной точки прямоугольника. Может быть значением типа double или кортежем из double и LengthType. |
| width | Ширина прямоугольника. Может быть значением типа double или кортежем из double и LengthType. |
| height | Высота прямоугольника. Может быть значением типа double или кортежем из double и LengthType. |
| fill | Цвет заливки или стиль рисования для прямоугольника. Может быть объектом Color, значением перечисления Paint или идентификатором сервера рисования. Необязательный параметр. |
| stroke | Цвет обводки или стиль рисования для контура прямоугольника. Может быть объектом Color, значением перечисления Paint или идентификатором сервера рисования. Необязательный параметр. |
| id | Уникальный идентификатор элемента прямоугольника. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки построителя элемента прямоугольника. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
