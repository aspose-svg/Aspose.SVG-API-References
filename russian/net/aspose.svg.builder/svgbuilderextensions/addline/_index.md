---
title: "SVGBuilderExtensions.AddLine"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddLine. Добавляет конфигурацию элемента line в построитель"
type: docs
weight: 350
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addline/
---
## AddLine<TBuilder>(*this TBuilder, Action&lt;SVGLineElementBuilder&gt;*) {#addline_1}

Добавляет конфигурацию элемента 'line' в конструктор.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    Action<SVGLineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'line'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLine<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGLineElementBuilder&gt;*) {#addline}

Добавляет элемент 'line' с указанными начальной и конечной точками и стилями в SVG‑конструктор.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1 = null, OneOf<double, (double, LengthType)> y1 = null, 
    OneOf<double, (double, LengthType)> x2 = null, OneOf<double, (double, LengthType)> y2 = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGLineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑builder, к которому будет добавлен элемент 'line'. |
| x1 | Координата x начальной точки линии. Может быть значением типа double или кортежем из double и LengthType. |
| y1 | Координата y начальной точки линии. Может быть значением типа double или кортежем из double и LengthType. |
| x2 | Координата x конечной точки линии. Может быть значением типа double или кортежем из double и LengthType. |
| y2 | Координата y конечной точки линии. Может быть значением типа double или кортежем из double и LengthType. |
| fill | Цвет заливки или стиль рисования линии. Может быть объектом Color, значением перечисления Paint или идентификатором paint‑server. Необязательный параметр. |
| stroke | Цвет обводки или стиль рисования линии. Может быть объектом Color, значением перечисления Paint или идентификатором paint‑server. Необязательный параметр. |
| id | Уникальный идентификатор элемента line. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки построителя элемента line. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
