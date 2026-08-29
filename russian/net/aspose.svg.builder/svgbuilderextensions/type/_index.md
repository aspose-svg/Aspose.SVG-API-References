---
title: "SVGBuilderExtensions.Type"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions Type. Устанавливает атрибут type элемента функции передачи компонента"
type: docs
weight: 2270
url: /ru/net/aspose.svg.builder/svgbuilderextensions/type/
---
## SVGBuilderExtensions.Type<TBuilder> method

Устанавливает атрибут 'type' элемента функции передачи компонентов.

```csharp
public static TBuilder Type<TBuilder>(this TBuilder builder, ComponentTransferType type)
    where TBuilder : ISVGElementBuilder, ITransferFunctionAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| type | Тип функции передачи компонента (например, linear, gamma). |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [ComponentTransferType](../../componenttransfertype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransferFunctionAttributeSetter](../../itransferfunctionattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
