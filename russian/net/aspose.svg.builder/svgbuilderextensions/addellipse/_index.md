---
title: "SVGBuilderExtensions.AddEllipse"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddEllipse. Добавляет конфигурацию элемента ellipse в билдер."
type: docs
weight: 120
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addellipse/
---
## AddEllipse<TBuilder>(*this TBuilder, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse_1}

Добавляет конфигурацию элемента 'ellipse' в построитель.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    Action<SVGEllipseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'ellipse'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddEllipse<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse}

Добавляет элемент 'ellipse' в построитель SVG, указывая его центр, радиусы и стили.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> rx = null, OneOf<double, (double, LengthType)> ry = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGEllipseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑билдера, к которому будет добавлен элемент 'ellipse'. |
| cx | Координата x центра эллипса. Может быть значением типа double или кортежем из double и LengthType. |
| cy | Координата y центра эллипса. Может быть значением типа double или кортежем из double и LengthType. |
| rx | Радиус по оси x эллипса. Может быть значением типа double или кортежем из double и LengthType. |
| ry | Радиус по оси y эллипса. Может быть значением типа double или кортежем из double и LengthType. |
| fill | Цвет заливки или стиль рисования для эллипса. Может быть объектом Color, значением перечисления Paint или идентификатором paint‑серверa. Необязательный параметр. |
| stroke | Цвет контура или стиль рисования для эллипса. Может быть объектом Color, значением перечисления Paint или идентификатором paint‑серверa. Необязательный параметр. |
| id | Уникальный идентификатор элемента эллипса. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки билдера элемента эллипса. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
