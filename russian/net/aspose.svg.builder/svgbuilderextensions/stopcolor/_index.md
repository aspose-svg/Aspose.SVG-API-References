---
title: "SVGBuilderExtensions.StopColor"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions StopColor. Устанавливает атрибут stop-color для SVG‑элемента, определяющий цвет на остановке градиента"
type: docs
weight: 2060
url: /ru/net/aspose.svg.builder/svgbuilderextensions/stopcolor/
---
## StopColor<TBuilder>(*this TBuilder, Color*) {#stopcolor_1}

Устанавливает атрибут 'stop-color' для SVG‑элемента, определяя цвет в точке остановки градиента.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| colorValue | Значение цвета, которое нужно установить. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StopColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#stopcolor}

Устанавливает атрибут 'stop-color' для SVG‑элемента, используя пользовательскую конфигурацию цвета.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
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
