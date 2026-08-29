---
title: "SVGBuilderExtensions.FloodColor"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions FloodColor. Устанавливает атрибут flood-color для SVG‑элемента, используя цвет System.Drawing."
type: docs
weight: 850
url: /ru/net/aspose.svg.builder/svgbuilderextensions/floodcolor/
---
## FloodColor<TBuilder>(*this TBuilder, Color*) {#floodcolor_1}

Устанавливает атрибут 'flood-color' для элемента SVG, используя цвет из System.Drawing.

```csharp
public static TBuilder FloodColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| colorValue | Цвет, который будет установлен как flood‑color. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FloodColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#floodcolor}

Устанавливает атрибут 'flood-color' для элемента SVG, используя пользовательскую настройку цвета.

```csharp
public static TBuilder FloodColor<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Делегат для настройки ColorBuilder. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
