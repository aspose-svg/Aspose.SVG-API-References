---
title: "SVGBuilderExtensions.Dur"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions Dur. Устанавливает атрибут dur, указывающий длительность анимации."
type: docs
weight: 760
url: /ru/net/aspose.svg.builder/svgbuilderextensions/dur/
---
## Dur<TBuilder>(*this TBuilder, TimeSpan*) {#dur_1}

Устанавливает атрибут 'dur', указывая длительность анимации.

```csharp
public static TBuilder Dur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| длительность | Длительность анимации. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dur<TBuilder>(*this TBuilder, [Dur](../../dur/)*) {#dur}

Устанавливает атрибут 'dur', указывая предопределённый тип длительности анимации.

```csharp
public static TBuilder Dur<TBuilder>(this TBuilder builder, Dur value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | Предопределённый тип длительности для анимации. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [Dur](../../dur/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
