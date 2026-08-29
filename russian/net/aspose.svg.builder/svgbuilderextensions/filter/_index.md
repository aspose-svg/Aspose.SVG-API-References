---
title: "SVGBuilderExtensions.Filter"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions Filter. Устанавливает атрибут filter для SVG‑элемента с использованием пользовательской конфигурации."
type: docs
weight: 840
url: /ru/net/aspose.svg.builder/svgbuilderextensions/filter/
---
## SVGBuilderExtensions.Filter<TBuilder> method

Устанавливает атрибут 'filter' для элемента SVG, используя пользовательскую конфигурацию.

```csharp
public static TBuilder Filter<TBuilder>(this TBuilder builder, 
    Action<FilterValueListBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Делегат для настройки FilterValueListBuilder. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [FilterValueListBuilder](../../filtervaluelistbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
