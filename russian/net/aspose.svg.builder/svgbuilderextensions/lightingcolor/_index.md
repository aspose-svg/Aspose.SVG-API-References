---
title: "SVGBuilderExtensions.LightingColor"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions LightingColor. Устанавливает атрибут lighting-color для SVG‑элемента, используя указанное значение цвета"
type: docs
weight: 1110
url: /ru/net/aspose.svg.builder/svgbuilderextensions/lightingcolor/
---
## LightingColor<TBuilder>(*this TBuilder, Color*) {#lightingcolor_1}

Устанавливает атрибут 'lighting-color' для элемента SVG, используя указанное значение цвета.

```csharp
public static TBuilder LightingColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| colorValue | Значение цвета для установки эффекта освещения. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LightingColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#lightingcolor}

Устанавливает атрибут 'lighting-color' для элемента SVG, используя пользовательскую конфигурацию цвета.

```csharp
public static TBuilder LightingColor<TBuilder>(this TBuilder builder, 
    Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Делегат для настройки цвета. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
