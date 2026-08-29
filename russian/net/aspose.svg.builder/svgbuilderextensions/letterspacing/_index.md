---
title: "SVGBuilderExtensions.LetterSpacing"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions LetterSpacing. Устанавливает атрибут letter-spacing для SVG‑элемента, используя числовое значение и определённый тип длины."
type: docs
weight: 1100
url: /ru/net/aspose.svg.builder/svgbuilderextensions/letterspacing/
---
## LetterSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#letterspacing_1}

Устанавливает атрибут 'letter-spacing' для элемента SVG, используя числовое значение и конкретный тип длины.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| значение | Значение межбуквенного интервала, которое нужно установить. |
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

## LetterSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#letterspacing}

Устанавливает атрибут 'letter-spacing' для элемента SVG, используя предопределённое значение интервала.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| значение | Предопределённое значение интервала, которое нужно установить. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
