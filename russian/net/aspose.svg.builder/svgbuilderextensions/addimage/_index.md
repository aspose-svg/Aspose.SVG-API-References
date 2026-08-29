---
title: "SVGBuilderExtensions.AddImage"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddImage. Добавляет конфигурацию элемента image в построитель."
type: docs
weight: 330
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addimage/
---
## AddImage<TBuilder>(*this TBuilder, Action&lt;SVGImageElementBuilder&gt;*) {#addimage}

Добавляет конфигурацию элемента 'image' в конструктор.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, 
    Action<SVGImageElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'image'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddImage<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, string, Action&lt;SVGImageElementBuilder&gt;*) {#addimage_1}

Добавляет элемент 'image' в SVG‑конструктор, встраивая внешнее изображение в документ SVG.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, string id = null, 
    Action<SVGImageElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип построителя SVG‑элементов, упрощающий использование fluent API. |
| билдер | Экземпляр SVG‑построителя, к которому будет добавлен элемент 'image'. |
| href | URL или ссылка на внешнее изображение. Необязательный параметр. |
| x | Координата x, где размещается изображение. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| y | Координата y, где размещается изображение. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| width | Ширина изображения. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| height | Высота изображения. Может быть типом double или ValueTuple с LengthType. Необязательный параметр. |
| id | Уникальный идентификатор элемента изображения. Необязательный параметр. |
| extend | Необязательное действие для дальнейшей настройки SVGImageElementBuilder. |

### Возвращаемое значение

Экземпляр построителя, позволяющий цепочку вызовов методов.

### См. также

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
