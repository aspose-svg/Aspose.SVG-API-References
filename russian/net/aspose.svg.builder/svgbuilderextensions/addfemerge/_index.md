---
title: "SVGBuilderExtensions.AddFeMerge"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions AddFeMerge. Добавляет конфигурацию элемента feMerge в построитель. Этот элемент позволяет применять эффекты фильтра одновременно, а не последовательно."
type: docs
weight: 240
url: /ru/net/aspose.svg.builder/svgbuilderextensions/addfemerge/
---
## SVGBuilderExtensions.AddFeMerge<TBuilder> method

Добавляет конфигурацию элемента 'feMerge' в конструктор. Этот элемент позволяет применять эффекты фильтра одновременно, а не последовательно.

```csharp
public static TBuilder AddFeMerge<TBuilder>(this TBuilder builder, 
    Action<SVGFEMergeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| настроить | Действие конфигурации для элемента 'feMerge'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [SVGFEMergeElementBuilder](../../svgfemergeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
