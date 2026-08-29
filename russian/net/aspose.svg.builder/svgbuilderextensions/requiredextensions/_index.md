---
title: "SVGBuilderExtensions.RequiredExtensions"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions RequiredExtensions. Устанавливает атрибут requiredExtensions у элемента SVG. Этот атрибут указывает, какие расширения требуются для обработки фрагмента SVG‑документа."
type: docs
weight: 1970
url: /ru/net/aspose.svg.builder/svgbuilderextensions/requiredextensions/
---
## SVGBuilderExtensions.RequiredExtensions<TBuilder> method

Устанавливает атрибут 'requiredExtensions' у SVG‑элемента. Этот атрибут указывает, какие расширения требуются для обработки фрагмента SVG‑документа.

```csharp
public static TBuilder RequiredExtensions<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IConditionalProcessingAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Построитель элемента SVG, на котором устанавливается атрибут. |
| значение | Строковое значение, представляющее требуемые расширения. |

### Возвращаемое значение

Исходный построитель элемента SVG для цепочки вызовов методов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../../iconditionalprocessingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
