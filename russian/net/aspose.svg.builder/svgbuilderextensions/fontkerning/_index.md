---
title: "SVGBuilderExtensions.FontKerning"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions FontKerning. Устанавливает атрибут font-kerning для SVG‑элемента, используя числовое значение и определённый тип длины"
type: docs
weight: 880
url: /ru/net/aspose.svg.builder/svgbuilderextensions/fontkerning/
---
## FontKerning<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontkerning_1}

Устанавливает атрибут 'font-kerning' для элемента SVG, используя числовое значение и конкретный тип длины.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| значение | Значение кернинга шрифта для установки. |
| type | Тип длины (например, px, em). |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FontKerning<TBuilder>(*this TBuilder, [Kerning](../../kerning/)*) {#fontkerning}

Устанавливает атрибут 'font-kerning' для элемента SVG, используя предопределённое значение кернинга.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, Kerning value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| значение | Предопределённое значение кернинга для установки. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [Kerning](../../kerning/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
