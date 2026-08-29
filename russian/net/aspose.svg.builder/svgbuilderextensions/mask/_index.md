---
title: "SVGBuilderExtensions.Mask"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions Mask. Устанавливает атрибут mask для SVG‑элемента, используя пользовательскую конфигурацию маски."
type: docs
weight: 1150
url: /ru/net/aspose.svg.builder/svgbuilderextensions/mask/
---
## SVGBuilderExtensions.Mask<TBuilder> method

Устанавливает атрибут 'mask' для элемента SVG, используя пользовательскую конфигурацию маски.

```csharp
public static TBuilder Mask<TBuilder>(this TBuilder builder, Action<MaskBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Делегат для настройки маски. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [MaskBuilder](../../maskbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
