---
title: "SVGBuilderExtensions.AddMetadata"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddMetadata. Добавляет конфигурацию элемента metadata в билдер. Элемент metadata используется для добавления метаданных в SVG‑контент."
type: docs
weight: 390
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

Добавляет конфигурацию элемента 'metadata' в конструктор. Элемент 'metadata' используется для добавления метаданных в SVG‑контент.

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| TElement | Тип, представляющий элемент 'metadata' в модели SVG. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'metadata'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
