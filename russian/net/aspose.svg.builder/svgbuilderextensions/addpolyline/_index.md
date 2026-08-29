---
title: "SVGBuilderExtensions.AddPolyline"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddPolyline. Добавляет конфигурацию элемента polyline в построитель."
type: docs
weight: 430
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addpolyline/
---
## AddPolyline<TBuilder>(*this TBuilder, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline_1}

Добавляет конфигурацию элемента 'polyline' в конструктор.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, 
    Action<SVGPolylineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'polyline'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolyline<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline}

Добавляет элемент 'polyline' в SVG‑конструктор, указывая его вершины и стили.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolylineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑построителя, к которому будет добавлен элемент 'polyline'. |
| точки | Массив чисел двойной точности, представляющий точки polyline (чередующиеся координаты x и y). |
| fill | Цвет заливки или стиль рисования для polyline. Может быть объектом Color, значением перечисления Paint или идентификатором сервера рисования. Необязательный параметр. |
| stroke | Цвет контура или стиль рисования для polyline. Может быть объектом Color, значением перечисления Paint или идентификатором сервера рисования. Необязательный параметр. |
| id | Уникальный идентификатор элемента polyline. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки построителя элемента polyline. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
