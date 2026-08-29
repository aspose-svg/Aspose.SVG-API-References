---
title: "SVGBuilderExtensions.SetAttribute"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions SetAttribute. Устанавливает атрибут на элемент SVG. Этот метод используется для добавления или изменения атрибута элемента SVG, который строится."
type: docs
weight: 2010
url: /ru/net/aspose.svg.builder/svgbuilderextensions/setattribute/
---
## SVGBuilderExtensions.SetAttribute<TBuilder> method

Устанавливает атрибут у SVG‑элемента. Этот метод используется для добавления или изменения атрибута создаваемого SVG‑элемента.

```csharp
public static TBuilder SetAttribute<TBuilder>(this TBuilder builder, string name, string value)
    where TBuilder : IAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Построитель элемента SVG, на котором устанавливается атрибут. |
| name | Имя атрибута, который нужно установить. |
| значение | Значение атрибута. |

### Возвращаемое значение

Исходный построитель элемента SVG для цепочки вызовов методов.

### См. также

* interface [IAttributeSetter](../../iattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
