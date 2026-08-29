---
title: "SVGBuilderExtensions.Max"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Max класса SVGBuilderExtensions. Устанавливает атрибут max, задающий максимальную продолжительность анимации."
type: docs
weight: 1160
url: /ru/net/aspose.svg.builder/svgbuilderextensions/max/
---
## Max<TBuilder>(*this TBuilder, TimeSpan*) {#max_1}

Устанавливает атрибут 'max', указывая максимальную длительность анимации.

```csharp
public static TBuilder Max<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| длительность | Максимальная продолжительность анимации. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Max<TBuilder>(*this TBuilder, [Media](../../media/)*) {#max}

Устанавливает атрибут 'max', указывая предопределённое условие максимальной длительности анимации.

```csharp
public static TBuilder Max<TBuilder>(this TBuilder builder, Media value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | Предопределённое условие максимальной продолжительности анимации. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [Media](../../media/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
