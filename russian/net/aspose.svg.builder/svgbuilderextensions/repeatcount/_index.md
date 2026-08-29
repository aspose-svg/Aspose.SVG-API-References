---
title: "SVGBuilderExtensions.RepeatCount"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод RepeatCount класса SVGBuilderExtensions. Устанавливает атрибут repeatCount, определяющий, сколько раз анимация должна повторяться"
type: docs
weight: 1950
url: /ru/net/aspose.svg.builder/svgbuilderextensions/repeatcount/
---
## RepeatCount<TBuilder>(*this TBuilder, int*) {#repeatcount_1}

Устанавливает атрибут 'repeatCount', определяя, сколько раз должна повторяться анимация.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, int value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | Количество раз, которое должна повторяться анимация. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatCount<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatcount}

Устанавливает атрибут 'repeatCount', определяя неограниченное количество повторов анимации с использованием предопределённого перечисления.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | Предопределённое бесконечное количество повторов для анимации. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
