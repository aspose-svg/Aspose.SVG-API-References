---
title: "SVGBuilderExtensions.StrokeDashArray"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод StrokeDashArray в SVGBuilderExtensions. Устанавливает атрибут stroke-dasharray для SVG‑элемента, определяя шаблон штрихов и пробелов, используемых для рисования обводки."
type: docs
weight: 2090
url: /ru/net/aspose.svg.builder/svgbuilderextensions/strokedasharray/
---
## StrokeDashArray<TBuilder>(*this TBuilder, params double[]*) {#strokedasharray_1}

Устанавливает атрибут 'stroke-dasharray' для SVG‑элемента, определяя шаблон штрихов и пробелов, используемых для отрисовки контура.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, params double[] dashArray)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| dashArray | Массив длин штрихов. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StrokeDashArray<TBuilder>(*this TBuilder, [Dash](../../dash/)*) {#strokedasharray}

Устанавливает атрибут 'stroke-dasharray' для SVG‑элемента, используя предопределённый шаблон штрихов.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, Dash value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| значение | Шаблон штрихов для установки. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [Dash](../../dash/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
