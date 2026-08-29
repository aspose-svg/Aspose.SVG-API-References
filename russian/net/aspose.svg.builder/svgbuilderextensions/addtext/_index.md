---
title: "SVGBuilderExtensions.AddText"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddText. Добавляет конфигурацию текстового элемента в конструктор."
type: docs
weight: 530
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

Добавляет конфигурацию элемента 'text' в построитель.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'text'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

Добавляет элемент 'text' с указанным содержимым и атрибутами в SVG‑построитель.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип конструктора SVG‑элементов, позволяющий цепочку вызовов. |
| билдер | Экземпляр конструктора, к которому будет добавлен элемент 'text'. |
| content | Текстовое содержимое, которое будет отображено внутри элемента 'text'. |
| x | Координата x для текстового элемента. Может быть значением типа double или кортежем из double и LengthType. |
| y | Координата y для текстового элемента. Может быть значением типа double или кортежем из double и LengthType. |
| fontSize | Размер шрифта для текста. Может быть значением типа double или кортежем из double и LengthType. |
| fontStyle | Стиль шрифта для текста (например, normal, italic, oblique). |
| fontFamily | Семейство шрифтов для текста (например, Arial, Verdana). |
| fontWeight | Вес (толщина) шрифта (например, normal, bold). |
| fill | Цвет заливки или стиль рисования для текста. Может быть значением Color, значением перечисления Paint или идентификатором paint‑server. |
| stroke | Цвет обводки или стиль рисования для текста. Может быть значением Color, значением перечисления Paint или идентификатором paint‑server. |
| id | Уникальный идентификатор элемента текста. |
| extend | Необязательное действие для дальнейшей настройки построителя элемента текста. |

### Возвращаемое значение

Экземпляр построителя для цепочки дальнейших добавлений или настроек.

### См. также

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
